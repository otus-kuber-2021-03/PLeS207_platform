FROM nginx:1.19-alpine

COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./homework.html  /var/www/html/homework.html 
RUN     chown -R 1001:1001 /var/cache/nginx && \
        chown -R 1001:1001 /var/log/nginx && \
        chown -R 1001:1001 /etc/nginx/conf.d && \
        touch /var/run/nginx.pid && \
        chown -R 1001:1001 /var/run/nginx.pid && \
        rm /etc/nginx/conf.d/default.conf
USER 1001
ENTRYPOINT ["nginx"]
CMD ["-g", "daemon off;"]
