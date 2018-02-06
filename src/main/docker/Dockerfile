FROM java:8-jre

MAINTAINER Francesco Muià <francescoMuia83@gmail.com>

ARG version

ADD /maven/docker-console-eureka-$version.jar /app/docker-console-eureka.jar

CMD ["java", "-Xmx200m", "-jar", "/app/docker-console-eureka.jar"]

EXPOSE 8761
