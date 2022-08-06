# docker/apache/Dockerfile
FROM httpd:2.4.51

COPY docker-php-apache.apache.conf /usr/local/apache2/conf/docker-php-apache.apache.conf

RUN echo "Include /usr/local/apache2/conf/docker-php-apache.apache.conf" \
    >> /usr/local/apache2/conf/httpd.conf