
**Fundamentals**

    Replication - (controlled by write concern)
    Sharding
    Quorum - Majority of nodes must be available for cluster to operate
    Consensus - Agreement among all the nodes for Primary/leader election (achieved via a voting mechanism)
    Causal consistency - Read your own writes (read happens on primary with performance overhead, default in mongo)
    Eventual consistency - Read happens from secondaries sacrificing consistency
    Journaling


**Replication**
  
    Single leader replication 
    Replica set - A cluster of MongoDB servers that implements replication and automated failover.
  
**Sharding**

    Sharding happens at collection level 

**Indexing strategies**

    Indexing happens at collection level
    https://docs.mongodb.com/manual/applications/indexes/
    Indices should be added programmatically rather than manually - This will reduce chances of human mistakes 

**Query execution and performance**

    Query plans used by query optimizer - https://docs.mongodb.com/v4.0/core/query-plans/
    Analyze query performance and execution stages - https://docs.mongodb.com/manual/tutorial/analyze-query-plan/
    Database profiling - https://docs.mongodb.com/manual/tutorial/manage-the-database-profiler/

**Data**

    Mongo and BSON - https://www.mongodb.com/json-and-bson
