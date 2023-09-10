FROM php:8.1-fpm

RUN apt-get update
RUN apt-get install -y curl git

WORKDIR /var/www

ENTRYPOINT [ "php-fpm" ]
