# Use Nginx base image
FROM nginx:alpine

# Remove default Nginx page and copy custom HTML
RUN rm -rf /usr/share/nginx/html/*
COPY index.html /usr/share/nginx/html

EXPOSE 80

