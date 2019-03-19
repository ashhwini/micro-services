FROM openjdk:11

RUN mkdir /src

WORKDIR /src

ADD target/zuul-0.0.1-SNAPSHOT.jar /src/zuul-0.0.1-SNAPSHOT.jar

EXPOSE 8092

RUN sh -c 'touch /src/zuul-0.0.1-SNAPSHOT.jar'

ENTRYPOINT ["java", "-jar","/src/zuul-0.0.1-SNAPSHOT.jar"]