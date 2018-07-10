#
FROM centos
MAINTAINER amviki
RUN yum update -y && yum install httpd -y && yum -y install initscripts && yum clean all && /usr/sbin/httpd -k start
