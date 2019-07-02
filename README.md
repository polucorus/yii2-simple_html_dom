PHP Simple HTML DOM Parser PHP 7.3
===============
PHP Simple HTML DOM Parser PHP 7.3

Installation
------------


```
php composer.phar require --prefer-dist serhatozles/yii2-simplehtmldom "dev-master"
```

```
php composer require cn13/simplehtmldom "dev-master"
```

or add

```
"serhatozles/yii2-simplehtmldom": "dev-master"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \cn13\simplehtmldom\SimpleHTMLDom::file_get_html('http://google.com'); ?>```