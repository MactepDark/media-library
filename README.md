Media Library
=============
Media Library module

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist mactepdark/medialibrary "*"
```

or add

```
"mactepdark/medialibrary": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \mactepdark\medialibrary\AutoloadExample::widget(); ?>```


```
'modules' => [
        'MediaLibrary' => [
            'class' => 'app\modules\MediaLibrary\Library',
        ],
    ],
```