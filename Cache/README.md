# Caching in distributed systems

*Introduction*

    Why? - To handle frequent or expensive queries and reduce system latency 
    
    Cache vs Database 
        Cache is not long term persistent store unlike database and stores data in memory  
        Cache is suitable for read heavy system 
        
    Where to cache? - in memory or between server and database (in memory or distrubuted cache) 
    
    Types of caching strategies 
        cache aside, read through, write through, write behind 
        https://medium.com/@mmoshikoo/cache-strategies-996e91c80303
    
    Staleness is the major issue that can happen in a cache 
    The basic approach to begin with is to use TTL (cache expiration) to ensure data is periodically refreshed 
    But there can still be staleness with cache expiration 
    To handle the inconsistencies or staleness, cache invalidation has to be done 
    Cache expiration blogs 
        https://redis.com/glossary/cache-invalidation/
        https://engineering.fb.com/2022/06/08/core-infra/cache-made-consistent/

    Further, cache eviction is another important part and requires proper algorithms 
    
    Thrashing
    
    Popular cache systems
        Redis
            https://aws.amazon.com/redis/
        Memcached   
        CDN

*Resources to read*

    Scaling Memcache at Facebook 
    https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf

        
