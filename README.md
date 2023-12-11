# Alpine based Dockerfile for various PHP8.x apps

[![Image](https://github.com/abalage/php-fpm-alpine/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/abalage/php-fpm-alpine/actions/workflows/docker-publish.yml)

A Dockerfile for PHP based on the official [PHP 8.3](https://hub.docker.com/_/php) FPM Alpine image. This is built for various apps with the following extensions:

- apcu
- bcmath
- bz2
- calendar
- dba
- exif
- gd
- gettext
- gmp
- imagick
- intl
- mysqli
- opcache
- pcntl
- pdo_mysql
- pdo_pgsql
- pgsql
- pspell
- soap
- sockets
- tidy
- timezonedb
- xmlrpc
- xsl
- zip

Docker builds and pushes are handled via GitHub actions: [.github/workflows](.github/workflows)

Work is based on following source(s):
- Dockerfile from https://github.com/ShGoudarzi/php-fpm-extended/blob/main/php-8.1/alpine/Dockerfile
