FROM nginx:1.29.4-trixie

RUN adduser --disabled-password --gecos '' web
USER web

COPY . /usr/share/nginx/html
