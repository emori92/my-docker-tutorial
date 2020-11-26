# get image
FROM httpd

# copy index.html
COPY ./index.html /usr/local/apache2/htdocs/

# set httpd.conf
COPY ./httpd.conf /usr/local/apache2/conf/httpd.conf

# port
EXPOSE 80

# version
LABEL imageversion=0.0.0 \
maintainer=emori92 \
lastupdate=2020-11-25

