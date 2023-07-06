FROM daocloud.io/library/nginx

RUN rm -rf /usr/share/nginx/html

COPY --chmod=0777 dist /usr/share/nginx/html

COPY nginx.conf /etc/nginx/nginx.conf