# Starts with a base image containing Java runtime
FROM eclipse-temurin:21-jdk-jammy

# Information around who maintains the image
MAINTAINER ivose

# Add the application's jar to the image
COPY target/loans-0.0.1-SNAPSHOT.jar loans-0.0.1-SNAPSHOT.jar

# execute the application
ENTRYPOINT ["java", "-jar", "loans-0.0.1-SNAPSHOT.jar"]
