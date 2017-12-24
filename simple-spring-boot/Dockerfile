FROM java:8-jre
MAINTAINER Dien Tran <dientm@github.com>

ADD ./target/simple-spring-boot.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/simple-spring-boot.jar"]

EXPOSE 8080