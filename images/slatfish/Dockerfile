FROM centos:7

RUN yum -y update && \
    yum -y upgrade && \
    yum -y install nginx && \
    yum -y install mysql-server && \
    yum -y install epel-release && \
    rpm -Uvh https://mirror.webtatic.com/yum/el7/webtatic-release.rpm && \
    yum -y install php72w php72w-cli php72w-fpm php72w-common php72w-devel
