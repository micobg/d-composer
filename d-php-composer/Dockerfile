FROM php:alpine

# PHP PDO MySQL suppport
RUN docker-php-ext-install pdo pdo_mysql

# Install PHP Composer
WORKDIR /usr/local/bin
RUN php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
RUN php composer-setup.php
RUN php -r "unlink('composer-setup.php');"
RUN ln -s composer.phar composer

WORKDIR /root
