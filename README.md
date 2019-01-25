# Java Sandbox
*A simple skeleton for rapid Test Driven Prototyping and Experiments (TDP+E) with Java.*

## Requirements
- Java >= 1.8.x
- Maven >= 3.5.x

## Packages
- Junit 5 Jupiter API and Engine
- Maven Surefire Plugin

## Test, Build and Run
```
mvn clean test package verify
java -cp target\sandbox-0.0.1-SNAPSHOT.jar de.dlqx.sandbox.App
```
