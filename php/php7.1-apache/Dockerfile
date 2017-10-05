FROM merorafael/php-apache:7.1
LABEL maintainer="Boik Su <boik@tdohacker.org>"

RUN apt-get update && apt-get install -y bzip2 p7zip-full

COPY ./provision.sh /provision.sh

CMD ["/provision.sh"]
