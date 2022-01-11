FROM nginx:1.21

RUN mkdir /app

WORKDIR /app

COPY ./public /app/public

COPY ./conf/default.conf /etc/nginx/conf.d/default.conf
