# Stack
PHP 7.2
Laravel
Composer
Ansible


# Startup

```bash
sudo apt-get update &&
sudo apt-get install software-properties-common &&
sudo apt-add-repository ppa:ansible/ansible &&
sudo apt-get update &&
sudo apt-get install ansible -y &&
sudo apt update && sudo apt upgrade -y
```

Установка Composer 20.04

sudo apt install php-cli unzip

cd ~
curl -sS https://getcomposer.org/installer -o /tmp/composer-setup.php

HASH=`curl -sS https://composer.github.io/installer.sig

echo $HASH

php -r "if (hash_file('SHA384', '/tmp/composer-setup.php') === '$HASH') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"

sudo php /tmp/composer-setup.php --install-dir=/usr/local/bin --filename=composer

composer

после установки SQL

cd ~

composer create-project --prefer-dist laravel/laravel travellist

cd travellist
php artisan
php artisan serve

composer update

#Nginx
Проверка конфигурации
sudo nginx -t

