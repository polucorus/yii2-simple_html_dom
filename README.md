PHP Simple HTML DOM Parser PHP 7.3
===============
PHP Simple HTML DOM Parser PHP 7.3

Installation
------------


```
php composer.phar require --prefer-dist cn13/yii2-simple_html_dom "1.0"
```
OR
```
composer require --prefer-dist cn13/yii2-simple_html_dom "1.0"
```


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \cn13\simplehtmldom\SimpleHTMLDom::file_get_html('http://google.com'); ?>```