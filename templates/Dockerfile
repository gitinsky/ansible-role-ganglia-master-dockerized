FROM gitinsky/baseimage:0.1.4
MAINTAINER Git In Sky <support@gitinsky.com>

RUN \
  apt-get update && \
  apt-get -y install ganglia-webfrontend && \
  cp /etc/ganglia-webfrontend/apache.conf /etc/apache2/conf-enabled/

ADD ./rc.local /etc/rc.local

EXPOSE 80
