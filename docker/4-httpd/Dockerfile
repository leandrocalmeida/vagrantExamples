FROM ubuntu:20.04
RUN apt-get -qq update && DEBIAN_FRONTEND=noninteractive apt-get install -y apache2 --no-install-recommends tzdata 
COPY public-html/index.html /var/www/html/
EXPOSE 80
CMD apachectl -D FOREGROUND
