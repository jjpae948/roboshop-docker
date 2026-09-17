FROM nginx:1.24.0-alpine3.17-slim
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/nginx.conf 
COPY static/ /usr/share/nginx/html/
COPY nginx.conf /etc/nginx/nginx.conf