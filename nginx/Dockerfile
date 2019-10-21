FROM nginx:1.17.4

RUN apt-get update && apt-get install -y nginx-extras

USER www-data

CMD ["nginx" "-g" "'daemon off;'"]
