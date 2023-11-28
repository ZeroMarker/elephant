# elephant

[How to Install and Use Composer on Ubuntu 22.04 | Step-by-Step](https://www.cherryservers.com/blog/how-to-install-composer-ubuntu)

```sh
sudo apt install php php-curl -y

curl -sS https://getcomposer.org/installer -o composer-setup.php

sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer

sudo composer self-update

composer -v

composer create-project laravel/laravel laravel

laravel --version

php artisan serve
```

[Laravel PHP command not found](https://stackoverflow.com/questions/26376516/laravel-php-command-not-found)

```sh
# ~/.bashrc
export PATH="~/.composer/vendor/bin:$PATH"
export PATH="~/.config/composer/vendor/bin:$PATH" 
```