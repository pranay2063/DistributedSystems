
**Fundamentals**

    Collection, Database, Cluster
    
    Replication - writes are controlled by write concern property, reads can be configured via read preferences property
    Sharding
    Quorum - Majority of nodes must be available for cluster to operate
    Consensus - Agreement among all the nodes for Primary/leader election (achieved via a voting mechanism)
    Causal consistency - Read your own writes (read happens on primary with performance overhead, default in mongo)
    Eventual consistency - Read happens from secondaries sacrificing consistency
    Journaling

    Replica is a copy of a dataset
    Replica set is a group of replicas of a dataset
    Different replicas reside on different servers
    A server is not a part of multiple relica sets (in other words, a server keeps one replica)
    Shard is a subset of data that is kept on server (shard is also called partition)
    Data is partitioned across different servers for horizontal scaling
    Each shard has a replica set
    So, in a cluster, if there are 3 shards of data with a replica set of size 3, the cluster must have 9 nodes

    Mongo queries can not be done via a DNS exposed via load balancer because of its architecture leader/follower
    Mongo queries are done via driver with a seed of cluster nodes specified in the configuration
    Driver can query an online node and any online node can return cluster configuration (details regarding leader etc)

    MongoDB is ACID compliant at document level

**Replication**
  
    Single leader replication 
    Replica set - A cluster of MongoDB servers that implements replication and automated failover
    What happens when primary is down?
    https://stackoverflow.com/questions/48611485/mongo-behaviour-once-master-is-down
  
**Sharding**

    Sharding happens at collection level 

**Indexing strategies**

    Indexing happens at collection level
    https://docs.mongodb.com/manual/applications/indexes/
    Indices should be added programmatically rather than manually - This will reduce chances of human mistakes 

**Concurrency control**

    Reader-writer locks, Intent locks at global, database and collection level
    Concurrency at document level is achieved using wiredTiger engine which uses optimistic concurrency
    https://www.mongodb.com/docs/manual/faq/concurrency/

    MongoDB is ACID compliant at document level
    https://stackoverflow.com/questions/7149890/what-did-mongodb-not-being-acid-compliant-before-v4-really-mean

**Query execution and performance**

    Query plans used by query optimizer - https://docs.mongodb.com/v4.0/core/query-plans/
    Analyze query performance and execution stages - https://docs.mongodb.com/manual/tutorial/analyze-query-plan/
    Database profiling - https://docs.mongodb.com/manual/tutorial/manage-the-database-profiler/

    Projection
        Limit the response data from mongo query
        https://www.mongodb.com/docs/manual/tutorial/project-fields-from-query-results/

**Data**

    Mongo and BSON - https://www.mongodb.com/json-and-bson
