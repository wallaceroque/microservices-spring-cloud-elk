FROM openjdk
MAINTAINER Wallace Roque <wallacerock@gmail.com>
ADD target/zipkin-service.jar zipkin-service.jar
#ENTRYPOINT ["java", "$JAVA_OPTIONS", "-jar", "/zipkin-service.jar"]
CMD java $JAVA_OPTIONS -jar /zipkin-service.jar
EXPOSE 9411