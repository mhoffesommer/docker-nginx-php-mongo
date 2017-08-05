# docker-nginx-php-mongo
Docker image based on Alpine linux with nginx, php-fpm and mongo driver.

## Ports
This image exposes ports 80 and 443. In order to use XDebug it also exposes
ports 22 and 9000.

## Volumes
This image exposes:
- /var/www; put web root into /var/www/web

## Usage

```
docker run -v /my_web_root:/var/www/web -p 80:80 mhoffesommer/nginx-php-mongo
```
