FROM nginx
COPY nginx.conf /etc/nginx/nginx.conf
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "<h1>Hi, I am from APP-1</h1>" > /usr/share/nginx/html/index.html