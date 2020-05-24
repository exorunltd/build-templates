FROM php:7.2-apache
WORKDIR /opt/app
COPY . . 
RUN rm -rf /var/www/html/
RUN ln -s /opt/app /var/www/html
RUN echo '. /etc/apache2/envvars && apache2 -DFOREGROUND' >> /usr/bin/start.sh