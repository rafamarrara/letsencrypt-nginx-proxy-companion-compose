## letsencrypt_nginx_proxy_companion with docker-compose

This repository contains reference docker-compose file for a variety of [nginx-proxy](https://github.com/nginx-proxy/nginx-proxy) with [letsencrypt-nginx-proxy-companion](https://github.com/nginx-proxy/docker-letsencrypt-nginx-proxy-companion) setup.

All the docker-compose file assume the existence of a docker network called `nginx-proxy`. You'll have to create it with `docker network create nginx-proxy` before you can use any of the example file.
