FROM composer:latest

RUN docker-php-ext-install mysqli pdo pdo_mysql

EXPOSE 8181

WORKDIR /app
COPY . /app

RUN composer install
CMD composer install; php artisan serve --host=0.0.0.0 --port=8181
