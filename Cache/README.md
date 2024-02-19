# Caching in distributed systems


Why? - To handle frequent or expensive queries and reduce system latency <br>
Cache vs Database <br>
    Cache is not long term persistent store unlike database and stores data in memory  
    Cache is suitable for read heavy system 
    
Where to cache? - in memory or between server and database (in memory or distrubuted cache) <br>


Types of caching strategies <br>
    cache aside, read through, write through, write behind 
    https://medium.com/@mmoshikoo/cache-strategies-996e91c80303

Staleness is the major issue that can happen in a cache <br>
The basic approach to begin with is to use TTL (cache expiration) to ensure data is periodically refreshed <br>
But there can still be staleness with cache expiration <br>
To handle the inconsistencies or staleness, cache expiration has to be done <br>
Cache expiration blogs <br>
    https://redis.com/glossary/cache-invalidation/
    https://engineering.fb.com/2022/06/08/core-infra/cache-made-consistent/

Thrashing <br>

Popular cache systems <br>
    Redis
        https://aws.amazon.com/redis/
    Memcached     
