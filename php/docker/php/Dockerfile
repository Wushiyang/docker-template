FROM php:5.6-fpm
LABEL maintainer="18368095041@163.com"
# RUN docker-php-ext-install mysql
RUN docker-php-ext-install mysqli
RUN pecl install xdebug-2.5.4 \
    && pecl install http://pecl.php.net/get/redis-3.1.2.tgz \
    && docker-php-ext-enable redis xdebug