FROM nginx
RUN mkdir -p /var/cache/nginx/client_temp && \
    chmod -R 777 /var/cache/nginx
COPY index.html /usr/share/nginx/html/index.html
EXPOSE 8080
