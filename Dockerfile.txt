FROM nginx:alpine

COPY default.conf /etc/nginx/conf.d/
COPY project/ /usr/share/nginx/html/