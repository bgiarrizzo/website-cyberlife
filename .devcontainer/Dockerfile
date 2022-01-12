FROM nginx:alpine

RUN sed -i "s|/usr/share/nginx/html|/workspace|g" /etc/nginx/conf.d/default.conf

ADD . /workspace

VOLUME [ "/workspace" ]