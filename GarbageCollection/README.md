Concurrency and parallelism 
- https://stackoverflow.com/questions/1897993/what-is-the-difference-between-concurrent-programming-and-parallel-programming

Basics, algorithms and types of garbage collection - 
- https://en.wikipedia.org/wiki/Garbage_collection_(computer_science)
- https://en.wikipedia.org/wiki/Tracing_garbage_collection#Generational_GC_(ephemeral_GC)
- https://howtodoinjava.com/java/garbage-collection/revisiting-memory-management-and-garbage-collection-mechanisms-in-java/
- https://howtodoinjava.com/java/garbage-collection/all-garbage-collection-algorithms/

Java GC docs
- https://docs.oracle.com/javase/9/gctuning/toc.htm


Default Garbage Collector in JVM currently - G1 (Garbage First)
- https://docs.oracle.com/javase/9/gctuning/garbage-first-garbage-collector.htm#JSGCT-GUID-ED3AB6D3-FD9B-4447-9EDF-983ED2F7A573
- https://www.oracle.com/technical-resources/articles/java/g1gc.html
- G1 tuning https://backstage.forgerock.com/knowledge/kb/article/a75965340


How to debug, analyze GC issues and do GC tuning - 
- https://stackoverflow.com/questions/1393486/error-java-lang-outofmemoryerror-gc-overhead-limit-exceeded
- https://docs.oracle.com/javase/9/gctuning/garbage-first-garbage-collector-tuning.htm#JSGCT-GUID-90E30ACA-8040-432E-B3A0-1E0440AB556A


GC Glossary
1. Tracing
2. Generational GC
3. Mark and Sweep 
4. Mark, Sweep and Compact
5. Stop and Copy 
6. CMS (Concurrent Mark Sweep)
7. GC execution - Concurrent, parallel, incremental and stop-the-world (pause)

Todo
Read G1 again and document relevant points

Additional articles - 
1. https://confluence.atlassian.com/doc/garbage-collector-performance-issues-200707997.html 
