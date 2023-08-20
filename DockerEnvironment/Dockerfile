FROM openjdk:11
EXPOSE 8000
ADD target/docker_test-0.0.1-SNAPSHOT.jar docker_test-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "docker_test-0.0.1-SNAPSHOT.jar"]