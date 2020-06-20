Streaming Tweets using Apache Nifi
=================
We will be using Apache Nifi to connect with Twitter to stream and store incoming tweets into HDFS 

Tools:  
Amazon AWS EC2 instance - based on Cloudera Quickstart VM 5.13.  https://github.com/aws-quickstart/quickstart-cloudera 
MobaXterm - I find MobaXterm an excellent All-In-One network application tool - https://mobaxterm.mobatek.net/


 

In this reference architecture, we support two options for deploying Cloudera's Enterprise Data Hub within a virtual private cloud (VPC). One option is to launch all the nodes within a public subnet providing direct internet access. The second option is to deploy all the nodes within a private subnet. The reference deployment builds both a public and private subnet, and the cluster can be deployed in either subnet using the configuration file.



### First bootstrap and download the wrapper ###
    cd kafka_source_dir
    gradle

Now everything else will work.

### Build a jar and run it ###
    ./gradlew jar
