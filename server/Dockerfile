FROM openjdk:11
ARG JAR_FILE=target/*jar
ADD /target/app-2.1.7.RELEASE.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]