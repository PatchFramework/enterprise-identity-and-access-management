FROM --platform=amd64 openresty/openresty:1.21.4.1-alpine-fat
 
RUN mkdir /var/log/nginx
 
RUN apk add --no-cache openssl-dev git gcc
RUN luarocks install lua-resty-openidc
 
ENTRYPOINT ["/usr/local/openresty/nginx/sbin/nginx", "-g", "daemon off;"]
#EXPOSE 80