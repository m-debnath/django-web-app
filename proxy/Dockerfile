FROM nginxinc/nginx-unprivileged:1.23-alpine

COPY ./default.conf /etc/nginx/conf.d/default.conf

USER root

RUN mkdir -p /vol/static
RUN chmod 755 /vol/static

USER nginx