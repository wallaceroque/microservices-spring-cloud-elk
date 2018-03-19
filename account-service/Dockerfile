FROM openjdk
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/account-service.jar account-service.jar
#ENTRYPOINT ["java", "-XX:+PrintFlagsFinal", "$JAVA_OPTIONS", "-jar", "/account-service.jar"]
CMD java $JAVA_OPTIONS -jar /account-service.jar
EXPOSE 2222