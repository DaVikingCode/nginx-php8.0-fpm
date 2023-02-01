# nginx-php8.0-fpm

This is a base image using nginx + php fpm monitored by supervisord.

- Bash
- PHP 8.0
- PostgreSQL driver
- MySQL driver
- PostgreSQL Client with pg_dump
- Imagick extension
- supervisor
- Composer
- Nodejs 16.13 + npm 8.1.2

Configuration : 

- PHP memory_limit = -1
- PHP post_max_size = 2G
- PHP upload_max_filesize = 1G
- PHP max_file_uploads = 300

It must be launched using tty option.
It uses the user 'www-data' (id 82).
