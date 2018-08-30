# Currency Exchange microservice Dockerfile

FROM java:8u45-jdk

COPY ./artifacts C:\Users\Suhail Gupta\.jenkins\workspace\Docker_Container\currencyconversionservice
WORKDIR C:\Users\Suhail Gupta\.jenkins\workspace\Docker_Container\currencyconversionservice

EXPOSE 8100

ENTRYPOINT ["java", "-jar", "currencyconversionservice-0.0.1-SNAPSHOT.jar", "com.suhail.microservices.currencyexchangeservice.currencyconversionservice.currencyconversionservice.CurrencyconversionserviceApplication"]
CMD [""]