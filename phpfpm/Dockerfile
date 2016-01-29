FROM xujif/docker-php7-cli:latest
MAINTAINER xujif <i@xujif.com>
RUN yum install -y php70w-fpm
RUN yum yum clean all
RUN mkdir -p /data
VOLUME ["/data"]
EXPOSE 9000
ENTRYPOINT ["/usr/sbin/php-fpm","-R", "-F"]
