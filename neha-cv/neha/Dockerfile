FROM openjdk:17
VOLUME /tmp
COPY build/libs/*.jar neha-cv-0.0.1-SNAPSHOT.jar
EXPOSE 8085
ENTRYPOINT ["java","-jar","/neha-cv-0.0.1-SNAPSHOT.jar"]