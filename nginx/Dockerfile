FROM nginx:latest

RUN apt-get update && \
    apt-get -y install nginx

COPY ./conf/default.conf /etc/nginx/conf.d

EXPOSE $PORT

CMD nginx -g "daemon off;"