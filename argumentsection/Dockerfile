FROM openjdk:8
LABEL org="BKFS"
ARG download_location= wget https://referenceappkhaja.s3-us-west-2.amazonaws.com/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar/springpetclinic.jar
ADD {$download_location} spring-petclinic.jar
EXPOSE 8080
CMD ["java", "-jar", "spring-petclinic.jar"]