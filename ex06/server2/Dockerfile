FROM nginx

COPY webapp /usr/share/nginx/html

ENTRYPOINT ["nginx", "-g", "daemon off;"]

#docker build -t ex05 .
#docker run -dit -p 8000:80 ex05