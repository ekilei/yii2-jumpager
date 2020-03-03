# yii2-jumpager

Jumpager является надстройкой над LinkPager, предназначен для адаптивных сайтов, удобен в применении на декстопе и на мобильных устройствах.

Jumpager is an add-on above the LinkPager, designed for adaptive sites, convenient for use on the desktop and on mobile devices.


```angular2html
<?php echo \ekilei\jumpager\Jumpager::widget([
      'pagination' => $pages,
]); ?>
```
![ScreenShot](https://raw.github.com/ekilei/yii2-jumpager/master/screen/1.png)

### Отображение в десктопной версии
View in desktop

![ScreenShot](https://raw.github.com/ekilei/yii2-jumpager/master/screen/2.png)

### Отображение в мобильной версии
View in mobile

![ScreenShot](https://raw.github.com/ekilei/yii2-jumpager/master/screen/3.png)

### Поле ввода вместо селекта
Input field instead of select 

```angular2html
<?php echo \ekilei\jumpager\Jumpager::widget([
      'pagination' => $pages,
      'type' => 'input',
]); ?>
```
![ScreenShot](https://raw.github.com/ekilei/yii2-jumpager/master/screen/4.png)

### Установка
Install

```
composer require ekilei/yii2-jumpager "dev-master"
```
