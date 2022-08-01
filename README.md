# nginx-php8.0-fpm

This is a base image using nginx + php fpm monitored by supervisord.

- PHP 8.0
- Postgresql driver
- Imagick extension
- supervisor
- Composer
- Nodejs 16.13 + npm 8.1.2

It must be launched using tty option.
It uses the user 'www-data' (id 82).
