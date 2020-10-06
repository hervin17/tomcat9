FROM httpd:latest
RUN  mkdir /usr/local/apache2/docs/
COPY ./www/ /usr/local/apache2/docs/
COPY ./httpd-vhosts.conf /usr/local/apache2/conf/extra/
COPY ./httpd.conf /usr/local/apache2/conf/
