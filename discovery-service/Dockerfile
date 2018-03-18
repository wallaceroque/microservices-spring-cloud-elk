FROM openjdk
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/discovery-service.jar discovery-service.jar
#ENTRYPOINT ["java", "$JAVA_OPTIONS", "-jar", "/discovery-service.jar"]
CMD java $JAVA_OPTIONS -jar /discovery-service.jar
#EXPOSE 8761