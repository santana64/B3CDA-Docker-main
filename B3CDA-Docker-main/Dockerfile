FROM php:8.3-apache
RUN docker-php-ext-install mysqli
COPY . /var/www/html/
COPY ./your_sql_file.sql /docker-entrypoint-initdb.d/
