FROM maven:3.9.9-eclipse-temurin-17

WORKDIR /app

COPY pom.xml ./
COPY src ./src

RUN mvn package

CMD ["sh", "-c", "exec java ${JAVA_OPTS:--Xms64m -Xmx256m} -jar target/words.jar"]
