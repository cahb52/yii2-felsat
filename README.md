Generador de fel en pdf
=======================
Genera un pdf al recibir el xml de la sat

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist cahb52/yii2-felsat "*"
```

or add

```
"cahb52/yii2-felsat": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \cahb52\fel\FelSat::widget(); ?>```