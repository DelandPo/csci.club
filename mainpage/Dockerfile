FROM nginx:alpine
COPY nginx.conf /etc/nginx/nginx.conf
COPY /static /var/web/static
COPY /index.html /var/web/index.html
CMD ["nginx", "-g", "daemon off;"]