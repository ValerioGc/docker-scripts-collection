FROM php:8.3-apache

# Dependencies
RUN apt-get update && apt-get install -y \
    libzip-dev zip unzip git curl vim libmariadb-dev \
    && docker-php-ext-install pdo_mysql zip
    
# Init script
COPY init.sh /usr/local/bin/init.sh
RUN chmod +x /usr/local/bin/init.sh

WORKDIR /var/www/html