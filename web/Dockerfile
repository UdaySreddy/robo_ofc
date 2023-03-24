FROM nginx
RUN rm -rf /etc/nginx/conf.d/default.conf
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/
COPY default.conf /etc/nginx/nginx.conf
