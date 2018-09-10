FROM centos:latest
MAINTAINER hiclock dotclock@hotmail.com

RUN yum update
RUN yum upgrade

ADD install.sh /data/install/
RUN sh /data/install/install.sh
