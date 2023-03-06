FROM ubuntu:20.04
# FROM maven
# FROM maven
RUN apt update
RUN apt install git -y
RUN DEBIAN_FRONTEND=noninteractive apt-get install maven
WORKDIR /tmp/
RUN git clone https://github.com/kekcment/App44.git
WORKDIR  /tmp/App44/
RUN mvn package
# default-jdk maven