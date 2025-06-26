FROM nginx
RUN mkdir -p /var/cache/nginx/client_temp && \
    chown -R 101:0 /var/cache/nginx
COPY index.html /usr/share/nginx/html/index.html
EXPOSE 8080
