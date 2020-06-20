Apache Kafka
=================
See our [web site](http://kafka.apache.org) for details on the project.

You need to have [Gradle](http://www.gradle.org/installation) and [Java](http://www.oracle.com/technetwork/java/javase/downloads/index.html) installed.

Kafka requires Gradle 4.5 or higher.

Java 8 should be used for building in order to support both Java 8 and Java 10 at runtime.

### First bootstrap and download the wrapper ###
    cd kafka_source_dir
    gradle

Now everything else will work.

### Build a jar and run it ###
    ./gradlew jar
