
    
*Databases*

    Optimizing SQL queries
    Indexes (Faster read)
    Horizontal partitioning (Sharding) - using consistent hashing
    Master-slave architecture (in case of machine/database server failure)

    Concurrency control 
        Uses locks
        Types - Optimistic locking and pessimistic locking
        Optimistic Locking / Optimistic Concurrency Control (OCC) 
            Transactions run without acquiring locks 
            Verifies whether the resource has been updated by other workers before committing transaction
            Rollbacks if the resource has already been committed by some other worker
            https://en.wikipedia.org/wiki/Optimistic_concurrency_control
            Increases throughput but does not work well in high data contention (more rollbacks)
        Pessimistic locking
            Acquires lock before running and committing the transactions
        
    In memory database
        https://aws.amazon.com/nosql/in-memory/
    
*Databases - SQL vs NoSQL*

    ORM (Object Relation Mapping) Model - https://stackoverflow.com/questions/1152299/what-is-an-object-relational-mapping-framework
    https://www.ibm.com/cloud/blog/sql-vs-nosql
    Scalability - Consistency, Availability and Partition Tolerance (CAP)
    Types - 
        Document Based- MongoDB (Document (JSON) -> Collection -> DB)
          Document is a unit
        Key-Value store - Redis
        Column-family based - Cassandra
        Graph DB - Neo4j
    
    AWS databases 
        https://aws.amazon.com/products/databases/



