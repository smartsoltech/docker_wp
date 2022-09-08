FROM wordpress

RUN set -ex ;\
    ln -s $PHP_INI_DIR/php.ini-production $PHP_INI_DIR/php.ini ;\
    docker-php-ext-install pdo_mysql

COPY app.ini $PHP_INI_DIR/conf.d/

