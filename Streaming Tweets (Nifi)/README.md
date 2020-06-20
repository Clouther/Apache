Streaming Tweets using Apache Nifi
=================
We will be using Apache Nifi to connect with Twitter to stream and store incoming tweets into HDFS 

Tools:

Amazon AWS EC2 instance - based on Cloudera Quickstart VM 5.13. Please follow the setup provided in the GitHub: https://github.com/aws-quickstart/quickstart-cloudera 
MobaXterm - I find MobaXterm an excellent All-In-One network application tool - https://mobaxterm.mobatek.net/


### First bootstrap and download the wrapper ###
    cd kafka_source_dir
    gradle

Now everything else will work.

### Build a jar and run it ###
    ./gradlew jar
