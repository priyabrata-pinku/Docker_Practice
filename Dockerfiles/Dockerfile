FROM tomcat:8.5.37-jre8
MAINTAINER pinku@gmail.com
RUN apt-get update
ADD https://time-tracker-war-file.s3.us-east-2.amazonaws.com/time-tracker-web-0.5.0-SNAPSHOT.war /usr/local/tomcat/webapps
WORKDIR /usr/local/tomcat/webapps
EXPOSE 8080
CMD ["catalina.sh", "run"]