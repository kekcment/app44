# FROM ubuntu:20.04
# # FROM maven
# RUN apt update
# RUN apt install git maven default-jdk -y
# WORKDIR /tmp/
# RUN git clone https://github.com/kekcment/App42.git
# WORKDIR  /tmp/App42/
# RUN mvn package

FROM maven:3.6.0-jdk-11-slim
COPY src /home/app/src
COPY pom.xml /home/app
RUN mvn -f /home/app/pom.xml clean package