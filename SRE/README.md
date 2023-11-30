[Google's SRE Book](https://sre.google/workbook/table-of-contents/)

SLI, SLO, SLA - 
  1. [Overview](https://sre.google/sre-book/service-level-objectives/)
  2. [Implementation](https://sre.google/workbook/implementing-slos/)

Agent (Sysdig/Nagios)<br/>
Montioring (Prometheus)<br/>
Alerting (AlertManager / PagerDuty)<br/>
Tracing (Jaeger)<br/>

OpenTelemetry - One stop library for traces, metrics and alerts

Crucial part of monitoring - Dashboards (Grafana)

Metric - [Prometheus](https://prometheus.io/docs/concepts/metric_types/)
  1. Counter (monotonically increasing values)
  2. Gauge (fluctuating values)
  3. Histogram
  4. Summary

Types of alerting
  1. SLO Based
  2. Metric alerting
  3. Any application alerts

IAC - https://en.wikipedia.org/wiki/Infrastructure_as_code 

Frameworks to expose host/service metrics (They can export metrics to a montitoring system like Prometheus)
  1. JMX
  2. Spring boot actuator 
