FROM centos:latest
MAINTAINER Ann
RUN yum -y install httpd
COPY index.html /var/www/html/
COPY animal*.jpg /var/www/html/
ENTRYPOINT ["/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80
