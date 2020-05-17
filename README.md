# redis-nginx

This a demo of the basic configuration for expose redis with nginx server.

## Requirments:

* docker
* docker-compose

## Run this demo:

```bash

git clone https://github.com/ripper2hl/redis-nginx.git
cd redis-nginx
docker-compose build
docker-compose up -d
redis-clit -p 8080 PING
```

## how it's works ?

* https://docs.nginx.com/nginx/admin-guide/load-balancer/tcp-udp-load-balancer/
* http://nginx.org/en/docs/stream/ngx_stream_core_module.html
