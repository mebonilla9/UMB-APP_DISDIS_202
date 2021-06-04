FROM adoptopenjdk/openjdk16:jre-16.0.1_9-alpine
COPY target/shipping-0.0.1-SNAPSHOT.jar .
CMD java -Xmx400m -Xms400m  -XX:TieredStopAtLevel=1 -noverify -jar shipping-0.0.1-SNAPSHOT.jar
EXPOSE 8080
