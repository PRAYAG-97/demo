FROM openjdk:8
ADD . /opt/
COPY target/HelloWorld-0.0.1-SNAPSHOT.jar /opt/
EXPOSE 8082
ENTRYPOINT java -jar /opt/HelloWorld-0.0.1-SNAPSHOT.jar
