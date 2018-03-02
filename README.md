# SpringBoot/HTTP2

Spring-Boot with REST using undertow over HTTP2 

# Requisites

1. [Java](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) 8+
2. [Maven](https://maven.apache.org/download.cgi) 3+

# Play

```
mvn spring-boot:run -pserver.port
```

# Access

```
https://localhost:8443/greeting
```

# Optionals

HTTP 1.1

```
mvn spring-boot:run -Dserver.http2.enabled=false
```

Server Port

```
mvn spring-boot:run -Dserver.port=9090
```


# References

[HTTP2 Configuration](http://www.baeldung.com/spring-boot-application-configuration
)
