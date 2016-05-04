FROM centos:latest
MAINTAINER KuuYee <kuuyee@qq.com>

RUN yum update -y
RUN yum install -y wget
RUN wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u72-b15/jdk-8u72-linux-x64.rpm

RUN rpm -ivh jdk-8*-linux-x64.rpm && rm jdk-8*-linux-x64.rpm

ENV JAVA_HOME /usr/java/latest