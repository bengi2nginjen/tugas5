FROM php:7.2-fpm
 
RUN docker-php-ext-install mysqli

FROM nginx:1.13.8

COPY /tugas5/* /srv/www/api