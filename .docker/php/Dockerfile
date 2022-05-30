FROM php:8.0-fpm

WORKDIR /app
RUN docker-php-ext-install mysqli
RUN chown -R www-data:www-data /app