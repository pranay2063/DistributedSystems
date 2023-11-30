[Google's SRE Book](https://sre.google/workbook/table-of-contents/)

SLI, SLO, SLA - 
  1. [Overview](https://sre.google/sre-book/service-level-objectives/)
  2. [Implementation](https://sre.google/workbook/implementing-slos/)

Observability stack 
  1. Montioring (Prometheus)
  2. Alerting (AlertManager / PagerDuty)
  3. Tracing (Jaeger)
  4. Dashboards - (Grafana / Kibana)
  5. Agent (Sysdig)

Prometheus
  1. Pull based monitoring system - https://prometheus.io/docs/introduction/overview/
  2. Metrics
     - Counter (monotonically increasing values), Gauge (fluctuating values), Histogram, Summary
     - https://prometheus.io/docs/concepts/metric_types/
  4. Rules
    - Recording rules, Alerting rules
     
Types of alerting
  1. SLO Based
  2. Metric alerting
  3. Event based alerting

IAC - https://en.wikipedia.org/wiki/Infrastructure_as_code <br/>
OpenTelemetry - One stop library for traces, metrics and alerts

Frameworks to expose host/service metrics (They can export metrics to a montitoring system like Prometheus)
  1. JMX
  2. Spring boot actuator 
