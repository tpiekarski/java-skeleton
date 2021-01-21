# java-skeleton
*A simple skeleton for rapid Test Driven Prototyping and Experiments with Java SE and EE*

## Branches
- JavaSE
- JavaEE

## Requirements
- JDK >= 1.8.x and <= 15
- Maven >= 3.5.x

## Packages
- Junit 5 Jupiter API and Engine
- Maven Assembly Plugin
- Maven Compile Plugin
- Maven Surefire Plugin

## Test, Build and Run
```
mvn clean test package verify
java -cp target/skeleton-0.0.1-SNAPSHOT.jar de.dlqx.skeleton.App
java -cp target/skeleton-0.0.1-SNAPSHOT-jar-with-dependencies.jar de.dlqx.skeleton.App
```
