FROM openjdk:17
ADD ./target/food-to-save-docker-redis-cep-0.0.1-SNAPSHOT.jar /usr/src/food-to-save-docker-redis-cep-0.0.1-SNAPSHOT.jar
WORKDIR usr/src
ENTRYPOINT ["java","-jar", "food-to-save-docker-redis-cep-0.0.1-SNAPSHOT.jar"]
