# Microservices-Configurations
This repository will store environment specific configurations for the microservices for my different microservices projects that will be used by Spring Cloud Config.

The naming convention for the file is :
{spring.application.name}-{env}.properties

You can verify if the configuration is getting loaded in Spring Cloud Config Server by accessing below URL Locally:
    http://localhost:8888/{spring.application.name}/{env}
    Ex- http://localhost:8888/PROBANK-ACCOUNTS-SERVICE/prd

