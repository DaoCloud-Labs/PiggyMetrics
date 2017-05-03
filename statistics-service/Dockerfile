FROM java:8-jre
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

ADD /usr/src/project/target/statistics-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/statistics-service.jar"]

EXPOSE 7000