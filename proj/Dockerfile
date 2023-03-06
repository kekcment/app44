FROM ubuntu:20.04
# FROM maven
RUN apt update
RUN apt install git default-jdk maven -y
WORKDIR /tmp/
RUN git clone https://github.com/kekcment/App44.git
WORKDIR  /tmp/App44/
RUN mvn package
