FROM php:8.1-fpm

WORKDIR /var/www/laravel/

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer --version=2.6.5

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
                       mc nano git \
    && docker-php-ext-install pdo pdo_mysql \



