FROM ubuntu:latest
MAINTAINER Noel Presti "noelxp@gmail.com"
ENV REFRESHED_AT 2021-5-14
RUN apt-get update
RUN apt-get -y -q install nginx
RUN mkdir -p /var/www/html
ADD nginx/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/nginx.conf
EXPOSE 80

