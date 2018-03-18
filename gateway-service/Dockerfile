FROM openjdk
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/gateway-service.jar gateway-service.jar
#ENTRYPOINT ["java", "$JAVA_OPTIONS", "-jar", "/gateway-service.jar"]
CMD java $JAVA_OPTIONS -jar /gateway-service.jar
EXPOSE 8765