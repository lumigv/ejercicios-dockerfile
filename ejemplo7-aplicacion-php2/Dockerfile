FROM php:8.2-apache
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
#ADD src /var/www/html/
EXPOSE 80
ENV DB_USER user1
ENV DB_PASS asdasd
ENV DB_NAME usuarios
ENV DB_HOST db
#ADD script.sh /usr/local/bin/script.sh
#ADD sql/schema.sql /opt
#RUN chmod +x /usr/local/bin/script.sh
#CMD ["/usr/local/bin/script.sh"]