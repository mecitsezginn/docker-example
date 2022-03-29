FROM php:7-apache
COPY index.php /var/www/html/index.php

# calisacak port no
EXPOSE 80
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]