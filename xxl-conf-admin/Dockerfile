FROM openjdk:8-jdk-alpine
MAINTAINER yy

#ENV PARAMS=""

ADD target/xxl-conf-admin-*.jar /app.jar

#ENTRYPOINT ["java", "-jar", "$PARAMS /app.jar"]
#ENTRYPOINT ["sh","-c","java -jar /app.jar $PARAMS"]
ENTRYPOINT ["sh","-c","java -jar /app.jar "]
