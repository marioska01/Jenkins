FROM ubuntu
MAINTAINER Jeganathan Swaminathan <jegan@tektutor.org>

ENV HTTP_PROXY http://192.168.101.52:8080
ENV HTTPS_PROXY http://192.168.101.52:8080
ENV NO_PROXY localhost,127.0.0.1,10.236.52.197
ENV http_proxy http://192.168.101.52:8080
ENV https_proxy http://192.168.101.52:8080
ENV no_proxy localhost,127.0.0.1,10.236.52.197
ENV JAVA_HOME /usr/lib/jvm/java-11-openjdk-amd64
ENV M2_HOME /root/apache-maven-3.6.1
ENV PATH "$PATH:$JAVA_HOME/bin:$M2_HOME/bin"

RUN apt-get update && apt-get install default-jdk git -y
#RUN apt-get update && apt-get install maven -y

COPY apache-maven-3.6.1-bin.tar.gz /root/apache-maven-3.6.1-bin.tar.gz
COPY settings.xml /root

RUN git config --global http.sslVerify false


