# Naming Service microservice Dockerfile

FROM java:8u45-jdk

COPY ./artifacts C:\Users\Suhail Gupta\.jenkins\workspace\Docker_Container\netflixeurekanamingserver
WORKDIR C:\Users\Suhail Gupta\.jenkins\workspace\Docker_Container\netflixeurekanamingserver

EXPOSE 8761

ENTRYPOINT ["java", "-jar", "netflixeurekanamingserver-0.0.1-SNAPSHOT.jar", "com.suhail.microservices.netflixeurekanamingserver.NetflixeurekanamingserverApplication"]
CMD [""]