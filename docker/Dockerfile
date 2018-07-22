FROM centos
MAINTAINER amviki

RUN mkdir /opt/publish/
ADD . /opt/publish/ 
RUN ln -s /opt/publish/jdk1.8.0_171/bin/java /bin/java 
RUN cd /opt/publish && java -jar AEM_6.2_publish-4503.jar -unpack && sh /opt/publish/crx-quickstart/bin/start
