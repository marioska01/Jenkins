FROM ubuntu
MAINTAINER Jeganathan Swaminathan <jegan@tektutor.org>

ENV http_proxy http://192.168.101.52:8080
ENV https_proxy http://192.168.101.52:8080
ENV no_proxy_hosts localhost,127.0.0.1,10.236.52.197

RUN apt-get update -y && apt-get install -y default-jdk git
RUN apt-get -y maven
