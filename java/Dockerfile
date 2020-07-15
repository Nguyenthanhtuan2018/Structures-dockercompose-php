# latest oracle openjdk is the basis
FROM openjdk:8
# copy jar file into container image under app directory
COPY SpringBootSocialJPA-0.0.1-SNAPSHOT.jar app/SpringBootSocialJPA-0.0.1-SNAPSHOT.jar
# expose server port accept connections
EXPOSE 8080
# start application
CMD ["java", "-jar", "app/SpringBootSocialJPA-0.0.1-SNAPSHOT.jar"]