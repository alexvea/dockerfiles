FROM debian:buster-slim

RUN apt-get update && apt-get install -y apache2
RUN a2enmod proxy_fcgi

CMD /usr/sbin/apache2ctl -D FOREGROUND
