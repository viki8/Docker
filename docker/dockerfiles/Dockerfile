#
FROM centos
MAINTAINER amviki
RUN yum update -y && yum install httpd -y && yum -y install initscripts && yum clean all
CMD apachectl -D FOREGROUND
