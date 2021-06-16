FROM nginx:1.18

ENV TZ=UTC

COPY ./infra/nginx/*.conf /etc/nginx/conf.d/

WORKDIR /var/www/html