FROM ubuntu
MAINTAINER Jeganathan Swaminathan <jegan@tektutor.org>

ENV HTTP_PROXY http://192.168.101.52:8080
ENV HTTPS_PROXY http://192.168.101.52:8080
ENV NO_PROXY localhost,127.0.0.1,10.236.52.197
ENV http_proxy http://192.168.101.52:8080
ENV https_proxy http://192.168.101.52:8080
ENV no_proxy localhost,127.0.0.1,10.236.52.197

RUN apt-get update && apt-get install default-jdk git -y
RUN apt-get update && apt-get install maven -y
