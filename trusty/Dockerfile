FROM buildpack-deps:trusty
MAINTAINER Li Yi <denverdino@gmail.com>
RUN sed -i 's/archive.ubuntu.com/mirrors.aliyun.com/' /etc/apt/sources.list
COPY pip.conf /root/.pip/pip.conf
