Kafka is grouped into topics <br>
A topic is a set of partitions <br>
A partition is stored in a server <br>
A partition is ordered and offset is used to the count the number of messages <br>
One one consumer can read from a partition <br>
But multiple publishers can publish to a partition <br><br>

Why is kafka so fast? - sequential IO and zero copy <br>
