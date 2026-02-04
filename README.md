# Kafka
Kafka hands-on

## Installing Apache Kafka on Windows

### Download kafka for windows:
Link:https://kafka.apache.org/community/downloads/

### Extraction of folder:
Extract the downloaded Kafka folder to c:\ folder path

### configure the Java
Download the latest Java version in the system
Link: https://www.oracle.com/in/java/technologies/downloads/

### Set path - environment vairables
1. Go to Control Panel
2. System Properties
3. Click on environment variables
4. Click on system variables 
5. select path and click on edit, and add the path of the installed java latest path till the bin folder
6. after successfull set, check for the version by opening power shell from the search bar
7. Type "java -version", press enter -> you should see the java version as mentioned in the screenshot below
   <img width="595" height="134" alt="image" src="https://github.com/user-attachments/assets/f8113e31-e170-4b81-82d7-b95fe0ef7f28" />


## Starting Zookeeper and Apache Kafka server on Windows

We need to download VS Code.
Link:https://code.visualstudio.com/docs/setup/windows

After downloading VS Code on Windows from the above link. Next step is to open the Kafka folder in VS Code.

<img width="246" height="146" alt="image" src="https://github.com/user-attachments/assets/ac5009d6-02be-42e6-8fff-ad081c047493" />

### How to set up Path: ( Need to configure  for Apache Server and zookeeper server
1.go to config folder -> check for server.properties file
2. search for workpath and now create a Kafka-logs folder undermain folder to 

Logs - > stores system logs
Kafka-logs which we created will store messages that send by producers and consumed by consumers 

before path changed:
<img width="235" height="40" alt="image" src="https://github.com/user-attachments/assets/35111430-03bc-4860-8206-4528e6b2b269" />

After path changed and added a folder named kafka-logs
<img width="656" height="344" alt="image" src="https://github.com/user-attachments/assets/dafbf22d-858e-4549-b7ff-1cf13d50449a" />

## First understand what is Kafka and ZooKeeper

### What is Apache Kafka?
Apache kafka is a distributed messaging  system used to store, send and process data in real time.

### In simple words
Kafka works like a high-speed message pipeline

### for Example
Application sends logs, events or data -> Kafka stores it -> other applications read it

### Some realworld examples:
1.payment transactions
2.website activity tracking 
3.log processing
4.realtime analytics

### Main Kafka components:
Producer: sends data
broker: kafka serer storing data
Topic:category where messagaes are stored
Consumer:reads data

## Now we will know what Apache Zookeeper?
Apache Zookeeper is a service that manages and coordinates distributed systems

Its act like a manager or coordinates for servers.


### Simple understanding about Zookeeper

-> It keeps track of which servers are alive
-> It also keeps track of who is the leader
->Also keep track of Cluster configuration.

It helps servers stay Synchronised.

<img width="305" height="167" alt="image" src="https://github.com/user-attachments/assets/f5ad5a53-e2ca-4ad3-9e01-e2f998cd95e1" />

<img width="241" height="405" alt="image" src="https://github.com/user-attachments/assets/5fb5f67c-d43a-4483-b612-bc59f0f08d46" />














