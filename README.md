# lemp-php7-newrelic-full
nginx + php7 + all needed extensions + supervisord + newrelic


It is base on [lemp-php7-full](https://hub.docker.com/r/mehrdadkhah/lemp-php7-full) and [php7 image](https://hub.docker.com/r/mehrdadkhah/php7) that contains:
 
 - php7 (official docker image)
 - nginx
 - last stable version of Redis extension (official version)
 - Intl extension (official version)
 - Apcu extension ([official build for php7](https://pecl.php.net/package/APCu))
 - Soap
 - PDO (MySQL, PostgreSQL, Sqlite)
 - GD
 - iconv
 - mbstring
 - composer
 - xdebug

and in ffmpeg tag image contain latest version of FFmpeg.
----------
##usage

    docker pull mehrdadkhah/lemp-php7-newrelic-full
