FROM nginx
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/conf.d/default.conf
RUN echo "helloworld" > /usr/share/nginx/html/index.html
EXPOSE 8080
