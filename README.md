YiiApp
======
yii-initial projects

Requirements
============
1.Installed XAMPP
2.Installed Git.
3.Installed Composer.

Using on Windows with XAMPP by Composer
================
```php

1.open cmd
2.cd /path/of/webserver   such as  c:\xampp\htdocs
3.git clone https://github.com/prawee/yiiapp.git your-project-name
4.cd your-project-name folder
5.composer self-update
6.composer --prefer-dist update
7.protected\vendor\yiisoft\yii\framework\yiic webapp c:\xampp\htdocs\your-project-name 
8.typing yes 
9.localhost/your-project-name

```

Update
======
2014-09-29 adding default composer.json