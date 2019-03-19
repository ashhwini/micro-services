FROM openjdk:11

RUN mkdir /src

WORKDIR /src

ADD target/eureka-0.0.1-SNAPSHOT.jar /src/eureka-0.0.1-SNAPSHOT.jar

EXPOSE 9090

RUN sh -c 'touch /src/eureka-0.0.1-SNAPSHOT.jar'

ENTRYPOINT ["java","-jar","/src/eureka-0.0.1-SNAPSHOT.jar"]