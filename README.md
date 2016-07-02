phpNT - Font Awesome
================================

### Описание:
### Поключает Font Awesome.
### [DEMO](http://phpnt.com/widget/font-awesome)

------------
### - [Поддержать phpNT](http://phpnt.com/donate/index)
------------

### Социальные сети:
 - [Канал YouTube](https://www.youtube.com/c/phpnt)
 - [Группа VK](https://vk.com/phpnt)
 - [Группа facebook](https://www.facebook.com/Phpnt-595851240515413/)

------------

Установка:

------------

```
php composer.phar require "phpnt/font-awesome" "*"
```
или

```
composer require phpnt/font-awesome
```

или добавить в composer.json файл

```
"phpnt/font-awesome": "*"
```

### Представление:
------------
```php
<?php
use phpnt\fontAwesome\FontAwesomeAsset;
FontAwesomeAsset::register($this);
// теперь элементы Font Awesome можно использовать в данном представлении
?>
```
```html
<div class="col-md-12">
    <i class="fa fa-camera-retro fa-lg"></i> fa-lg
    <i class="fa fa-camera-retro fa-2x"></i> fa-2x
    <i class="fa fa-camera-retro fa-3x"></i> fa-3x
    <i class="fa fa-camera-retro fa-4x"></i> fa-4x
    <i class="fa fa-camera-retro fa-5x"></i> fa-5x
</div>
<div class="col-md-12" style="margin-top: 40px;">
    <i class="fa fa-spinner fa-spin fa-3x fa-fw" style="color: #00a7d0;"></i>
    <span class="sr-only">Loading...</span>
    <i class="fa fa-circle-o-notch fa-spin fa-3x fa-fw" style="color: #00ca6d;"></i>
    <span class="sr-only">Loading...</span>
    <i class="fa fa-refresh fa-spin fa-3x fa-fw" style="color: #ce8483;"></i>
    <span class="sr-only">Loading...</span>
    <i class="fa fa-cog fa-spin fa-3x fa-fw" style="color: #7adddd;"></i>
    <span class="sr-only">Loading...</span>
    <i class="fa fa-spinner fa-pulse fa-3x fa-fw" style="color: #e3c300;"></i>
    <span class="sr-only">Loading...</span>
</div>

<div class="col-md-12" style="margin-top: 40px;">
    <div class="btn-group">
        <a class="btn btn-primary" href="#"><i class="fa fa-user fa-fw"></i> User</a>
        <a class="btn btn-primary dropdown-toggle" data-toggle="dropdown" href="#">
            <span class="fa fa-caret-down" title="Toggle dropdown menu"></span>
        </a>
        <ul class="dropdown-menu">
            <li><a href="#"><i class="fa fa-pencil fa-fw"></i> Edit</a></li>
            <li><a href="#"><i class="fa fa-trash-o fa-fw"></i> Delete</a></li>
            <li><a href="#"><i class="fa fa-ban fa-fw"></i> Ban</a></li>
            <li class="divider"></li>
            <li><a href="#"><i class="fa fa-unlock"></i> Make admin</a></li>
        </ul>
    </div>
</div>

<div class="col-md-12" style="margin-top: 40px;">
    <a class="btn btn-danger" href="#">
        <i class="fa fa-trash-o fa-lg"></i> Delete</a>
    <a class="btn btn-default btn-sm" href="#">
        <i class="fa fa-cog"></i> Settings</a>
    <a class="btn btn-lg btn-success" href="#">
        <i class="fa fa-flag fa-2x pull-left"></i> Font Awesome<br>Version 4.6.3</a>

    <div class="btn-group" style="margin-top: 40px;">
        <a class="btn btn-default" href="#">
            <i class="fa fa-align-left" title="Align Left"></i>
        </a>
        <a class="btn btn-default" href="#">
            <i class="fa fa-align-center" title="Align Center"></i>
        </a>
        <a class="btn btn-default" href="#">
            <i class="fa fa-align-right" title="Align Right"></i>
        </a>
        <a class="btn btn-default" href="#">
            <i class="fa fa-align-justify" title="Align Justify"></i>
        </a>
    </div>

    <div class="input-group margin-bottom-sm" style="margin-top: 40px;">
        <span class="input-group-addon"><i class="fa fa-envelope-o fa-fw"></i></span>
        <input class="form-control" type="text" placeholder="Email address">
    </div>
    <div class="input-group">
        <span class="input-group-addon"><i class="fa fa-key fa-fw"></i></span>
        <input class="form-control" type="password" placeholder="Password">
    </div>
</div>
```
------------
# Документация (примеры):
## [Font Awesome](http://fontawesome.io/examples/)
------------
### Версия:
### 0.0.1
------------
### Лицензия:
### [MIT](https://ru.wikipedia.org/wiki/%D0%9B%D0%B8%D1%86%D0%B5%D0%BD%D0%B7%D0%B8%D1%8F_MIT)
------------
