FROM nginx:alpine

COPY index.html /usr/share/nginx/html

RUN apk add curl

RUN curl -o /usr/share/nginx/html/dog.jpg https://placedog.net/1024
