# Starts with a base image containing Java runtime
FROM eclipse-temurin:21-jdk-jammy

# Information around who maintains the image
MAINTAINER ivose

# Add the application's jar to the image
COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar

# execute the application
ENTRYPOINT ["java", "-jar", "accounts-0.0.1-SNAPSHOT.jar"]

# docker build . -t eazybytes/accounts:S6
# docker run -p 8080:8080 eazybytes/accounts:S6
# docker run -d -p 8080:8080 eazybytes/accounts:S6 # -p 1234:8080
# docker ps; docker ps -a; docker start <id or name>; dcd ocker stop <id or name>;