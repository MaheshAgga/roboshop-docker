FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.confg
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY roboshop.conf /etc/nginx/default.d/nginx.conf
ADD static /usr/share/nginx/html/

