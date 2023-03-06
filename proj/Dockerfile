FROM tomcat:9.0
# FROM maven
RUN apt update
RUN apt install git -y
WORKDIR /tmp/
RUN git clone https://github.com/kekcment/App42.git
WORKDIR  /tmp/App42/
RUN mvn package