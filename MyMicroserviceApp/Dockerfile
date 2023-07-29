# For Java 13 installed on jenkins-slave(jenkins slave node)
FROM opt:jdk-13.0.1

# Refer to Maven build -> finalName
ARG JAR_FILE=target/MyMicroserviceApp-1.0-SNAPSHOT.jar

# cd /opt/app
WORKDIR /opt/app

# cp target/MyMicroserviceApp-1.0-SNAPSHOT.jar /opt/app/app.jar
COPY ${JAR_FILE} MyMicroserviceApp-1.0-SNAPSHOT.jar

# java -jar /opt/app/app.jar
ENTRYPOINT ["java","-jar","MyMicroserviceApp-1.0-SNAPSHOT.jar"]

## sudo docker run -p 8080:8080 -t docker-spring-boot:1.0
## sudo docker run -p 80:8080 -t docker-spring-boot:1.0
## sudo docker run -p 443:8443 -t docker-spring-boot:1.0
