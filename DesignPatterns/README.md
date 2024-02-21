
Summary - https://learn.microsoft.com/en-us/azure/architecture/patterns/

Popular design patterns in distributed systems 
1. Circuit breaker
   - https://learn.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker
   - States in a circuit breaker (CLOSED, OPEN, HALF-OPEN)
   - Library provind the implementation
        - https://github.com/resilience4j/resilience4j
        - https://spring.io/guides/gs/cloud-circuit-breaker
    
2. Multi-reactor pattern in Vert.x
    - https://vertx.io/docs/vertx-core/java/#_reactor_and_multi_reactor
    - https://stackoverflow.com/questions/23925968/tomcat-vs-vert-x
    - https://stackoverflow.com/questions/49772061/vertx-how-multithreading-works
3. Outbox pattern
    - https://docs.aws.amazon.com/prescriptive-guidance/latest/cloud-design-patterns/transactional-outbox.html
    - Use case - Dual writes - https://thorben-janssen.com/dual-writes/
4.  CQRS
    - https://martinfowler.com/bliki/CQRS.html
5. Backend For FrontEnd (BFF)
    - https://learn.microsoft.com/en-us/azure/architecture/patterns/backends-for-frontends
  



