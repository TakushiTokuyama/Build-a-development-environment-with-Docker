FROM nginx

RUN apt-get update && apt-get install -y vim

EXPOSE 80

RUN rm -rf /etc/nginx/conf.d/

COPY ./conf.d/nginx.conf /etc/nginx/conf.d/