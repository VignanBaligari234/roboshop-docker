FROM nginx
RUN rm -rf /usr/share/ngix/html/index.html
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf
ADD static /usr/share/ngix/html/