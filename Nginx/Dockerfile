FROM nginx:1.15.9

COPY conf/default.conf.template /etc/nginx/conf.d/default.conf.template
COPY conf/nginx.conf /etc/nginx/nginx.conf
COPY conf/www/index.html /usr/share/nginx/html
COPY conf/www/images /usr/share/nginx/html/images

CMD /bin/bash -c "envsubst '\$PORT' < /etc/nginx/conf.d/default.conf.template > /etc/nginx/conf.d/default.conf" && nginx -g 'daemon off;'
