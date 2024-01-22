FROM debian
RUN apt-get update && apt-get install -y apache2
COPY /src/index.html /var/www/html/
EXPOSE 80
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
