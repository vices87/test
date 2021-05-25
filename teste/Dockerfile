FROM php:7.3-apache
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
RUN apt-get update && docker-php-ext-install pdo_mysql
RUN docker-php-ext-install mysqli pdo pdo_mysql
RUN echo "Docker file loaded"

//apachectl restart