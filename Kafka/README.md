# Definition
* Kafka = Kafa is a Streaming Platform
* Kafka is distributed system , which means it can scaleup as needed
* Latency = The time taken for a packet to be transferred across a network. You can measure this as one-way to its destination or as a round trip
* Throughput = The quantity of data being sent and received within a unit of time
* Partition = Kafka topics are devided into partitions, each partition contains records in a fixed order

# GitLab
* https://gitlab.com/classpath2

# ToRead
* Kafka can process large amount of data in a short amount of time.
* Kafka has low latency, making it possible to process the data in real-time. 
* Kafka is written in Scala & Java  
* Kafka can be used with different programming languages
* Kafka is not same as RabbitMQ
* Kafka is built to be scalable horizontally by adding more nodes
* Kafka is used for fault-tolerant storage as well as publishing and subscribing to a stream of records
* Kafka cluster is made up of a number of brokers
* Multiple brokers work together to build a Kafka cluster, which provides load balancing, reliable redundancy and failover
* Kafka maintains a numerical offset for each record in a partition. 
* Offset is unique id that identifies each record in the partition

# Features of Kaka
1. Kafka is a messaging system built for high throughput and fault tolerance
2. Kafka has a built-in patriation system known as a Topic
3. Kafka Includes a replication feature as well
4. Kafka provides a queue that can handle large amounts of data and move messages from one sender to another
5. Kafka can save the messages to storage and replicate them across the cluster
6. Kafka collaborates with Zookeeper for coordination and synchronization with other services
7. Apache Spark is well supported by Kafka

# Components of Kafka
1. Topic =  Topic is a category or feed in which records are saved and published
2. Producer = Producer is a data source for one or more Kafka topics that optimizes, writes, and publishes messages
3. Consumer = Data is read by consumers by reading messages from topics to which they have subscribed
4. Broker =  Broker is a server that works as part of a Kafka cluster
* ![image](https://user-images.githubusercontent.com/7721150/158395377-6b80af4f-5623-4de4-bb5d-bfcbd01d58fd.png)

# Kafka API Architecture
1. Producer API
2. Consumer API
3. Streams API
4. Connect API
* ![image](https://user-images.githubusercontent.com/7721150/158396968-10b54f36-099a-4ab1-b3c7-155dc4e191ee.png)



# Traditional methods of message transfer
1. Message Queuing
* ![image](https://user-images.githubusercontent.com/7721150/158394305-b5ca6855-9141-417c-9cb0-83ce64c47457.png)
2. Publisher - Subscriber Model
* ![image](https://user-images.githubusercontent.com/7721150/158394503-f32c19a9-b9a0-4572-845b-ee9ca7af1aaa.png)


# Differences
| #Kafka | #Others |
| :---: | :---: | 
|  Consumers can retrieve messages from Kafka by pulling | RabbitMQ sends messages to consumers and monitors their load. It determines how many messages each consumer should be processing at any one time |
| Kafka keeps messages for a period of time (default is 7 days) after they've been received|RabbitMQ eliminates messages immediately after the consumer confirms them |
| | |
| | |

# Terminology
* Fault tolerance = fall back
* Resilient 
* Broker = Server 
* Kafka Node = Kafka Server
* Publish = Write 
* Subscribe = Read 
* Topic = Logic name / Logical entity which will be sending the data 
* Message is pushed to Partition 
* Round Robin Strategy 
* Cluster ---> Broker ( Server ) ----> Topic ---> Partition 
* Throughput = The quantity of data 
* Zookeeper is internal component to manage Brokers 
* Zookeeper cluster 
* Broker = Server / Node 
* Distributed Systems 
* Redundancy = Replica 
* Read ( Consumer ) & Write Operation ( Producer ) 
* Set of brokers form Cluster 
* Leader Partition & Follower Partitions are there in each Broker
* Partition is replicated 
* Produce messages to Topic 
* Producer & Consumer are independent 
* Consumer should subscribe to Topic 
* Producer will send data / message to Broker 
* Consumer is single threaded 
* Offset number is different for different partition 
* Offset is unique Id to 
* Producer 
* Consumer 
* Schema 
* Message 
* Broker 
* Partition 
* Topic 
* Leader Partition & Follower Partition 
* Leader Broker 
* Producer Partition 
* 3 Acknowledgement Modes 
* Producer Record 
* Key 
* Value 
* Console Producer 
* Java Producer 
* OffSet 
* Delivery Semantics -- At least once, At most once, Exactly once 
* Latency = The time taken for a packet to be transferred across a network
* Buffer Size 
* Message Size 
* Throwput 
* Durable on Disk 
* Data Retention 
* Data Format 
* Replica 
* Message or Data Format ( JSON ) 

# Reference
* [Apache Kafka Tutorial](https://www.youtube.com/watch?v=hyJZP-rgooc)
* [Apache Kafka Tutorial For Beginners](https://www.youtube.com/watch?v=U4y2R3v9tlY)
