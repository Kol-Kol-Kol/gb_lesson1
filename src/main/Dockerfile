FROM eclipse-temurin:8-jdk-ubi9-minimal
COPY ./java ./src
RUN mkdir ./out
RUN javac -sourcepath ./src -d out src/ru/geekbrains/lesson1/sample/Main.java
CMD java -classpath ./out ru.geekbrains.lesson1.sample.Main