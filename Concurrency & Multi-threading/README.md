
**Basics**

    Concurrency, Parallelism and Asynchrony
        https://stackoverflow.com/questions/4844637/what-is-the-difference-between-concurrency-parallelism-and-asynchronous-methods
        https://stackoverflow.com/questions/1050222/what-is-the-difference-between-concurrency-and-parallelism

    Concurrency and multi-threading 
        https://www.educative.io/blog/multithreading-and-concurrency-fundamentals
        Concurrency is achieved through multi-threading 
        Multi-threading allows creation of multiple threads within a process, executing independently but concurrenctly sharing process resources
        Threads can run in parallel if there are multiple CPU cores 

    Thread Safety, Thread local

    Locking (Concurrency control) - Pessimistic locking, Optimistic locking 

    Mutex and Semaphore 
        https://stackoverflow.com/questions/771347/what-is-mutex-and-semaphore-in-java-what-is-the-main-difference
        Mutex is different from semaphore as it has ownership attached to it
        A thread needs to acquire mutex before releasing it 
        Mutex is not binary semaphore
        Mutex is a locking mechanism and semaphore is a signalling mechanism 
        Semaphore are of two types - binary and counting 

**Concurrency in Java**

    Thread class and runnable interface (for multi-threading)
    AtomicInteger
    Volatile keyword https://www.geeksforgeeks.org/volatile-keyword-in-java/  
    ThreadLocal, Volatile, None of the two 
    https://en.wikipedia.org/wiki/Double-checked_locking#Usage_in_Java

    Concurrent data structures 
        HashMap vs HashTable vs ConcurrentHashMap
        https://stackoverflow.com/questions/510632/whats-the-difference-between-concurrenthashmap-and-collections-synchronizedmap

    BlockingQueue
    Synchronization using synchronized keyword
        https://www.geeksforgeeks.org/synchronization-in-java/
    Implementing mutex in Java
        https://stackoverflow.com/questions/5291041/is-there-a-mutex-in-java
  
    Reentrant lock (One of the ways to implement mutex)
        Only one thread can lock a reentrant lock
        Same thread can acquire lock on a resource multile times   

    Semaphore
        https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Semaphore.html
        https://www.geeksforgeeks.org/semaphore-in-java/  
    Condition 
        https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/locks/Condition.html
    Object vs Condition
        https://stackoverflow.com/questions/51063963/object-vs-condition-wait-vs-await
    Stop execution of a thread https://www.geeksforgeeks.org/java-concurrency-yield-sleep-and-join-methods/

    Locks and Synchronization by MIT
        https://web.mit.edu/6.005/www/fa15/classes/23-locks/
    Concurrency API: Synchronization and Locks
        https://winterbe.com/posts/2015/04/30/java8-concurrency-tutorial-synchronized-locks-examples/
    Producer Consumer solution using Lock
        https://javarevisited.blogspot.com/2015/06/java-lock-and-condition-example-producer-consumer.html#axzz7FdFkypML

    Reentrance problem 
        https://stackoverflow.com/questions/2799023/what-exactly-is-a-reentrant-function
    Reentrancy
        https://en.wikipedia.org/wiki/Reentrancy_(computing)
    Cases
        https://stackoverflow.com/questions/13983753/under-what-conditions-can-a-thread-enter-a-lock-monitor-region-more-than-once
    How to make a thread sleep
        https://stackoverflow.com/questions/9587673/thread-sleep-vs-timeunit-seconds-sleep 
    Thread Scheduling
        https://stackoverflow.com/questions/24649842/scheduleatfixedrate-vs-schedulewithfixeddelay

**ExecutorService and CompletableFuture**   

    If we create a thread manually, we will have to maintain it
    Java provides ExecutorService which allows allocating threads to a pool and maintains their lifecycle
    If there is a need of synchronization among threads, ExecutorService can be a good option
    TaskExecutor, TaskScheduler, ScheduledThreadPoolExecutor
    
    If there is a need to work on the results of the execution threads, completableFuture can be a better option
    Future - an object which is used to store a future result (Response of completableFuture)
    Callback - a function that is a passed as an argument to a method and is executed after the method is done executed

**Problems in concurrency and critical section** 

    https://www.geeksforgeeks.org/synchronization-in-java/
    Deadlock, Starvation, Livelock, Race condition

**Leetcode issue analysis**

    Busy looping (why to avoid loops in concurrency problems)
        https://leetcode.com/problems/print-foobar-alternately/discuss/1170524/Java-Sync-lock-resource
    Busy waiting vs Sleep waiting
        https://www.baeldung.com/cs/os-busy-waiting
    Locking solution
        https://leetcode.com/problems/print-foobar-alternately/discuss/1600113/Java-ReentrantLock-%2B-Condition-%2B-Volatile
    IllegalMonitorStateException
        https://stackoverflow.com/questions/7126550/java-wait-and-notify-illegalmonitorstateexception
    Synchronization on large number of threads
        https://leetcode.com/problems/building-h2o/
    
    Questions
        https://leetcode.com/discuss/interview-question/1125380/rubrik-system-coding-interview-question
