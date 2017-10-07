FROM ubuntu
RUN apt-get update && apt-get install -y apache2 && apt-get install -y vim && apt-get install -y curl 

#EXPOSE 80

#ENV APACHE_RUN_USER www-data
#ENV APACHE_RUN_GROUP www-data
#ENV APACHE_LOG_DIR /var/log/apache2
#ENV APACHE_LOCK_DIR /var/lock/apache2
#ENV APACHE_PID_FILE /var/run/apache2.pid

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]