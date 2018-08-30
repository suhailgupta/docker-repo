# Currency Conversion microservice Dockerfile

FROM java:8u45-jdk

COPY ./artifacts C:\Users\Suhail Gupta\.jenkins\workspace\Docker_Container\currencyexchangeservice
WORKDIR C:\Users\Suhail Gupta\.jenkins\workspace\Docker_Container\currencyexchangeservice

EXPOSE 8100

ENTRYPOINT ["java", "-jar", "currencyexchangeservice-0.0.1-SNAPSHOT.jar", "com.suhail.microservices.currencyexchangeservice.currencyexchangeservice.CurrencyexchangeserviceApplication"]
CMD [""]