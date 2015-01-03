FROM infoslack/docker-nginx

MAINTAINER Daniel Romero <infoslack@gmail.com>

RUN rm -f /etc/nginx/conf.d/*

COPY nginx.conf /etc/nginx/nginx.conf
COPY app.conf /etc/nginx/conf.d/app.conf
