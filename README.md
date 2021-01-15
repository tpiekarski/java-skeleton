# java-skeleton
*A simple skeleton for rapid Test Driven Prototyping and Experiments with Java SE and EE*

## Branches
- JavaSE
- JavaEE

## Requirements
- JDK >= 1.8.x
- Maven >= 3.5.x

## Packages
- Java Enterprise 8 API
- Junit 5 Jupiter API and Engine
- Maven Compile Plugin
- Maven Surefire Plugin

## Test, Build and Run
```
mvn clean test package verify
java -cp target\skeleton-0.0.1-SNAPSHOT.jar de.dlqx.skeleton.App
```
