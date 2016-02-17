FROM xujif/php7-cli:latest
MAINTAINER xujif <i@xujif.com>
RUN yum install  -y  python-setuptools
RUN easy_install supervisor
RUN yum clean all
ENTRYPOINT ["supervisord","-n"]