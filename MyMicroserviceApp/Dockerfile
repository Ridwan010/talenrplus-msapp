FROM openjdk:11
EXPOSE 8080 
ADD target/MyMicroserviceApp.jar MyMicroserviceApp.jar
ENTRYPOINT ["java","-jar","MyMicroserviceApp.jar"]

# Refer to Maven build -> finalName
#ARG JAR_FILE=target/MyMicroserviceApp.jar

# cd /opt/app
#WORKDIR /opt/app

# cp target/MyMicroserviceApp-1.0-SNAPSHOT.jar /opt/app/app.jar
#COPY ${JAR_FILE} MyMicroserviceApp.jar

# java -jar /opt/app/app.jar
#ENTRYPOINT ["java","-jar","MyMicroserviceApp.jar"]

## sudo docker run -p 8080:8080 -t docker-spring-boot:1.0
## sudo docker run -p 80:8080 -t docker-spring-boot:1.0
## sudo docker run -p 443:8443 -t docker-spring-boot:1.0
