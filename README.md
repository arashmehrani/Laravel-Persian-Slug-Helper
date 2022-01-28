# Laravel-Persian-Slug-Helper
Laravel Persian Slug Helper

## how to use ?
1. Copy Helpers.php to: `\app\Http`
2. Then in your `composer.json` add Helpers.php file location we just copied to autoload for register it: <br>
  `    "autoload": {
        "files": [
            "app/Http/Helpers.php"
        ],
    },`
3. Done.

For Example:
```sh

$title = 'تست @#$ شماره 123 aBCd';
$slug = Helpers::makeSlug($title);
/// outpot
"تست-شماره-123-abcd"
```
