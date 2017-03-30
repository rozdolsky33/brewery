FROM jboss/base-jdk:8

COPY build/libs/eureka-1.0.0.jar /opt/jboss/

EXPOSE 8761

USER jboss

CMD java -jar /opt/jboss/eureka-1.0.0.jar -Xmx1024m
