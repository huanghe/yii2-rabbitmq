mq for yii2
===========
基于php-amqplib的封装

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist hahaxixi-rabbitmq/yii2-rabbit "*"
```

or add

```
"hahaxixi-rabbitmq/yii2-rabbit": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \hahaxixi\rabbit\AutoloadExample::widget(); ?>```