FROM nginx
COPY default.conf /etc/nginx/conf.d/
ENV TZ Asia/Shanghai
ENTRYPOINT ["bash", "-c", "nginx -g 'daemon off;'"]

