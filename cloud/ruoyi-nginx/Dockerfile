FROM daocloud.io/library/nginx

RUN rm -rf /usr/share/nginx/html

COPY ruoyi-ui/dist/* /usr/share/nginx/html

COPY cloud/ruoyi-nginx/nginx.conf /etc/nginx/nginx.conf