[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/S6S0YXPX)

# How to Monitor, Audit and Gather Metrics on a Spring Boot Application

When dealing with a multi-component application such as in a microservice architecture it is very important to manage, audit, gather metrics, health check-up and monitor the different microservice applications or in our example Spring boot applications. With Spring boot framework there is a library that is easily accessible and configured to provide such production-ready features which is the Spring Boot Actuator. These features are accessible via JMX or Http endpoints.

In addition, there is also a community project which is known as Spring Admin that provides an administration that provides a centralized place to access the details submitted by all the registered clients.

## Dockerized

```
docker build -t czetsuya/terawarehouse-adminserver .
docker run -d -p 8761:8761 czetsuya/terawarehouse-admin-server
```

### References

 * https://github.com/codecentric/spring-boot-admin
 * https://codecentric.github.io/spring-boot-admin/current
 * https://docs.spring.io/spring-boot/docs/current/reference/html/production-ready-endpoints.html
 
## Repositories

 - https://github.com/terawarehouse
 
## Authors

 * **Edward P. Legaspi** - *Java Architect* - [czetsuya](https://github.com/czetsuya)