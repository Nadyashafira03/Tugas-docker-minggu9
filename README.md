FROM nginx:alpine
LABEL maintainer="nadshafira08@gmail.com"
COPY index.html /usr/share/nginx/html/index.html
EXPOSE 80
