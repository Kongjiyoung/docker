FROM ubuntu

WORKDIR /etc/init.d

RUN apt-get update && apt-get -y install nginx

CMD ["sh", "-c", "./nginx start && tail -f /dev/null"]
# CMD ["nginx", "-g", "daemon off;"]

#docker build -t zmxn/nginx .
#docker run -dit -p 8000:80 zmxn/nginx