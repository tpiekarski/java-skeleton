# Java Sandbox
*A simple skeleton for rapid Test Driven Prototyping and Experiments (TDP+E) with Java SE and EE*

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
java -cp target\sandbox-0.0.1-SNAPSHOT.jar de.dlqx.sandbox.App
```
