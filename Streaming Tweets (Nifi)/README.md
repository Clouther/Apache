Streaming Stock Tweets using Apache Nifi
=================
We will be using Apache Nifi to connect with Twitter to stream and store incoming tweets into HDFS 

Tools Used:
Amazon AWS EC2 instance - based on Cloudera Quickstart VM 5.13.  https://github.com/aws-quickstart/quickstart-cloudera 
MobaXterm - I find MobaXterm an excellent All-In-One network application tool - https://mobaxterm.mobatek.net/

Required:  
Twitter Developper Account - https://twitter.com/login?redirect_after_login=https%3A%2F%2Fdeveloper.twitter.com%2Fen%2Fapply%2Fuser.html

### First start your Amazon EC2 instance and connect through MobaXterm ###

(Insert Screenshot of MobaXterm)

### Start up and Connect to Nifi ###
    $ sudo service nifi start
    [Amazon Public DNS from EC2]:9999/nifi

(Insert Screenshot of empty Nifi)

Connect the GetTwitter Processor and fill in the appropriate keys based on the Twitter Developper Credentials

(Insert Screenshot)

Connect the GetTwitter Processor and fill in the appropriate keys based on the Twitter Developper Credentials
    
Full Nifi flow can be found in the XML file
