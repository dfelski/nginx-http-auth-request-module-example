FROM bitnami/nginx:latest

ADD default.conf /opt/bitnami/nginx/conf/server_blocks/my_server_block.conf
ADD index.html /opt/bitnami/nginx/html/private1/index.html
ADD index.html /opt/bitnami/nginx/html/private2/index.html

EXPOSE 8010

CMD ["nginx", "-g", "daemon off;"]
