FROM debian:bullseye-slim

RUN apt-get update && \
    apt-get -y install nginx

COPY ./default /etc/nginx/sites-enabled/default

ENV HOST 0.0.0.0

EXPOSE $PORT

CMD ["nginx","-g","daemon off;"]