# Definition
* Kafka = Kafa is a Streaming Platform
* Kafka is distributed system , which means it can scaleup as needed
* Latency = The time taken for a packet to be transferred across a network. You can measure this as one-way to its destination or as a round trip
* Throughput = The quantity of data being sent and received within a unit of time

# ToRead
* Kafka can process large amount of data in a short amount of time.
* Kafka has low latency, making it possible to process the data in real-time. 
* Kafka is written in Scala & Java  
* Kafka can be used with different programming languages
* Kafka is not same as RabbitMQ
* Kafka is built to be scalable horizontally by adding more nodes
* Kafka is used for fault-tolerant storage as well as publishing and subscribing to a stream of records

# Features of Kaka
1. Kafka is a messaging system built for high throughput and fault tolerance
2. Kafka has a built-in patriation system known as a Topic
3. Kafka Includes a replication feature as well
4. Kafka provides a queue that can handle large amounts of data and move messages from one sender to another
5. Kafka can save the messages to storage and replicate them across the cluster
6. Kafka collaborates with Zookeeper for coordination and synchronization with other services
7. Apache Spark is well supported by Kafka

# Differences
| #Kafka | #Others |
| :---: | :---: | 
|  Consumers can retrieve messages from Kafka by pulling | RabbitMQ sends messages to consumers and monitors their load. It determines how many messages each consumer should be processing at any one time |
| Kafka keeps them for a period of time (default is 7 days) after they've been received|RabbitMQ eliminates messages immediately after the consumer confirms them |
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
* Topic ---> Broker --> Partition 
* Throughput = The quantity of data 
* Zookeeper is internal component to manage Brokers 
* Zookeeper cluster 
* Broker = Server / Node 
* Distributed Systems 
* Redundancy = Replica 
* Read ( Consumer ) & Write Operation ( Producer ) 
* Set of brokers form Cluster 
* Leader Partition & Follower Partitions 
* Partition is replicated 
* Produce messages to Topic 
* Producer & Consumer are independent 
* Consumer should subscribe to Topic 
* Producer will send data / message to Broker 
* Consumer is single threaded 
* Offset number is different for different partition 
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
