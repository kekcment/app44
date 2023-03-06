# FROM ubuntu:20.04
# FROM maven
FROM maven:3.0.5
# RUN apt update
RUN apt install git -y
WORKDIR /tmp/
RUN git clone https://github.com/kekcment/App44.git
WORKDIR  /tmp/App44/
RUN mvn package
# default-jdk maven