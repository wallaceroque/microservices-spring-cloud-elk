FROM openjdk
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/customer-service.jar customer-service.jar
#ENTRYPOINT ["java", "-XX:+PrintFlagsFinal", "$JAVA_OPTIONS", "-jar", "/customer-service.jar"]
CMD java -XX:+PrintFlagsFinal $JAVA_OPTIONS -jar /customer-service.jar
EXPOSE 3333