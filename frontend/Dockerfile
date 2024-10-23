FROM nginx
COPY code /usr/share/nginx/html
RUN rm -rf /etc/nginx/nginx.conf
#RUN rm -rf /etc/nginx/conf.d
COPY expense.conf /etc/nginx/conf.d/expense.conf
