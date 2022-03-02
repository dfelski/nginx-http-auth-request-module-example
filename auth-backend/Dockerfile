FROM bitnami/nginx:latest

ADD default.conf /opt/bitnami/nginx/conf/server_blocks/my_server_block.conf

EXPOSE 8011
CMD ["nginx", "-g", "daemon off;"]
