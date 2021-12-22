
Concurrency, Parallelism and Asynchrony
- [StackOverflow: concurrency, parallelism, asynchronous methods](https://stackoverflow.com/questions/4844637/what-is-the-difference-between-concurrency-parallelism-and-asynchronous-methods)
- [StackOverflow: concurrency and parallelism](https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism)

Concurrency and multi-threading 
- [Educative](https://www.educative.io/blog/multithreading-and-concurrency-fundamentals)
- Concurrency is achieved through multi-threading 
- Multi-threading allows creation of multiple threads within a process, executing independently but concurrenctly sharing process resources
- Threads can run in parallel if there are multiple CPU cores 

Thread Safety, Thread local

Locking (Concurrency control) 
  1. Pessimistic locking 
  2. Optimistic locking 

Mutex and Semaphore 
- [StackOverflow](https://stackoverflow.com/questions/771347/what-is-mutex-and-semaphore-in-java-what-is-the-main-difference)
- Mutex is different from semaphore as it has ownership attached to it
- A thread needs to acquire mutex before releasing it 
- Mutex is not binary semaphore
- Mutex is a locking mechanism and semaphore is a signalling mechanism 
- Semaphore are of two types - binary and counting 

Concurrency in Java 
- Thread class and runnable interface (for multi-threading)
- AtomicInteger
- Volatile keyword
- Concurrent data structures (Eg: HashMap vs HashTable vs ConcurrentHashMap)
- [Synchronization using synchronized keyword](https://www.geeksforgeeks.org/synchronization-in-java/)
- [Implementing mutex in Java](https://stackoverflow.com/questions/5291041/is-there-a-mutex-in-java) 
- Reentrant lock (One of the ways to implement mutex)
- [Stop execution of a thread](https://www.geeksforgeeks.org/java-concurrency-yield-sleep-and-join-methods/)
- Articles
  - [Locks and Synchronization by MIT](https://web.mit.edu/6.005/www/fa15/classes/23-locks/) 
  - [Concurrency API: Synchronization and Locks](https://winterbe.com/posts/2015/04/30/java8-concurrency-tutorial-synchronized-locks-examples/)
  - [Producer Consumer solution using Lock](https://javarevisited.blogspot.com/2015/06/java-lock-and-condition-example-producer-consumer.html#axzz7FdFkypML)

[Problems in concurrency and critical section](https://www.geeksforgeeks.org/synchronization-in-java/)
- Deadlock
- Starvation
- Livelock
- Race condition
