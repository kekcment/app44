FROM tomcat:9.0
# FROM maven
RUN apt update
RUN apt install git maven -y
WORKDIR /tmp/
RUN git clone https://github.com/kekcment/App44.git
WORKDIR  /tmp/App44/
RUN mvn package
