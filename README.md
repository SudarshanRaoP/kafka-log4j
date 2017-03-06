# kafka-log4j
Log4j configuration to produce logs to Kafka.

# Build dependency: 
### Maven
```xml
<dependency>
    <groupId>org.apache.kafka</groupId>
    <artifactId>kafka-log4j-appender</artifactId>
    <version>0.9.0.0</version>
</dependency>
```

### SBT
```scala
libraryDependencies += "org.apache.kafka" % "kafka-log4j-appender" % kafkaVersion
```

# Usage (Java):
```java
Logger logger = Logger.getLogger(MyApp.class);  
logger.info("message from log4j appender");
```
