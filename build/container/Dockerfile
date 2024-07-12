FROM adoptopenjdk/openjdk17

RUN mkdir -P /engn001/test

COPY git-0.0.1-SNAPSHOT.jar /engn001/test

WORKDIR /engn001/test

ENTRYPOINT ["java", "-jar", "git-0.0.1-SNAPSHOT.jar"]