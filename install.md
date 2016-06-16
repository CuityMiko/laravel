### 安装composer
* curl -sS https://getcomposer.org/installer | php
* mv composer.phar /usr/local/bin/composer
* 现在只需要运行 composer 命令就可以使用 Composer 而不需要输入 php composer.phar。

### 采用中国镜像：
composer config -g repositories.packagist composer http://packagist.phpcomposer.com

### 安装 Laravel 程序
首先, 通过 Composer 下载 Laravel 安装程序:
composer global require "laravel/installer"

### 添加Laravel 环境变量：
    export PATH=$PATH:~/.composer/vendor/bin
    source ~/.bashrc

### 创建一个Laravel 应用
    laravel new blog

