# change php version (ex: php:7.1-apache)
FROM php:<<VERSION>>
# Installing packages for php
RUN apt-get update && apt-get install -y libpq-dev && docker-php-ext-install pdo pdo_pgsql