Streaming Stock Tweets using Apache Nifi
=================
We will be using Apache Nifi to connect with Twitter to stream and store incoming tweets into HDFS 

Tools Used:
Amazon AWS EC2 instance - based on Cloudera Quickstart VM 5.13.  https://github.com/aws-quickstart/quickstart-cloudera 
MobaXterm - I find MobaXterm an excellent All-In-One network application tool - https://mobaxterm.mobatek.net/

Required:  
Twitter Developper Account - https://twitter.com/login?redirect_after_login=https%3A%2F%2Fdeveloper.twitter.com%2Fen%2Fapply%2Fuser.html

### First start your Amazon EC2 instance and connect through MobaXterm ###

![MobaXterm - Start](https://user-images.githubusercontent.com/38193183/85236506-8d26b780-b3ec-11ea-8758-18f1a6586787.PNG)

### Start up and Connect to Nifi ###
    $ sudo service nifi start
    [Amazon Public DNS from EC2]:9999/nifi
    
![Nifi - Get Twitter](https://user-images.githubusercontent.com/38193183/85236518-9b74d380-b3ec-11ea-8f75-fd7880d55cd7.PNG)

Connect the GetTwitter Processor and fill in the appropriate keys based on the Twitter Developper Credentials

![Twitter Processor](https://user-images.githubusercontent.com/38193183/85231025-f8a75f80-b3c1-11ea-9e7a-1eee66dd69d6.PNG)
Connect the GetTwitter Processor and fill in the appropriate keys based on the Twitter Developper Credentials
    
Full Nifi flow can be found in the XML file


![Final Nifi Flow](https://user-images.githubusercontent.com/38193183/85236504-8c8e2100-b3ec-11ea-95d0-816caa257d40.PNG)
