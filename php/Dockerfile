FROM php:7.4-fpm
LABEL maintainer="Mr.Goose"

# Atualiza o SO
RUN docker-php-ext-install mysqli pdo_mysql
RUN apt-get update -y && apt-get upgrade -y
RUN apt-get install -y sudo curl vim git zip unzip

# devemos fazer isso apenas no modo dev, o Composer não deve estar disponível na produção
RUN apt-get update -y && apt-get upgrade -y
RUN curl --silent --show-error https://getcomposer.org/installer | php -- \
    --install-dir=/usr/local/bin --filename=composer