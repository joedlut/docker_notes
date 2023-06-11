FROM ubuntu:latest 
RUN apt -y install apache2
COPY file1 /var/www/html/
ADD file2.tar.gz /var/www/html/
CMD ["/sbin/httpd","-D","FOREGROUND"]
