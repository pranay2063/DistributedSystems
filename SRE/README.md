[Google's SRE Book](https://sre.google/workbook/table-of-contents/)

SLI, SLO, SLA - 
  1. [Overview](https://sre.google/sre-book/service-level-objectives/)
  2. [Implementation](https://sre.google/workbook/implementing-slos/)

Agent (Sysdig/Nagios)<br/>
Montioring (Prometheus)<br/>
Alerting (AlertManager / PagerDuty)<br/>
Tracing (Jaeger)<br/>
Dashboards - Grafana/Kibana <br />

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

IAC - https://en.wikipedia.org/wiki/Infrastructure_as_code 
OpenTelemetry - One stop library for traces, metrics and alerts

Frameworks to expose host/service metrics (They can export metrics to a montitoring system like Prometheus)
  1. JMX
  2. Spring boot actuator 
