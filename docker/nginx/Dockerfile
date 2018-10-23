FROM nginx:latest

RUN apt-get update && apt-get install -y vim

#COPY nginx.conf /etc/nginx/sites-enabled/default
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY common.conf /etc/nginx/common.conf
COPY nette.conf /etc/nginx/nette.conf
COPY php.conf /etc/nginx/php.conf