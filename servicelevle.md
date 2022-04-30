### Summary

Any Product app running on cars_platform requires a Service Level Agreement (SLA).

Well defined SLA‘s assure health/performance of products running on cars_platform. SLA's serve as
the foundation which product observability, monitoring and alerting are built from, ensuring the platform and business remain in sync.

### Definitions

**SLA** - a document defining the service and its availability requirements
requirements defined including what should be measured
severity levels correlated with requirements

**SLI** - creation of metrics/telemetry supporting requirements in the SLA demonstrates the performance and health of SLA

**SLO** - performance goals of each SLI supporting the SLAdefining threshold (rate of failure/success)  of individual monitors and service supporting the SLA
alerting rules that support the SLA

| Service Level   | Agreement               | Indicator                   | Objective                 |
| --------------- | :-----------------------: | :-----------------------: | :-----------------------: |
| Product/UX      | Responcible/Accountable   | Consulted/Informed        | Informed                  |
| Engineering     | Informed                  | Responcable/Accountable   | Responcible/Accountable   |

### The Way

Service levels inform each other. If SLA's are the challenge, then it's met by the creation of SLI's
and SLO's by engineering teams. SLI's are used by engineering teams to build observability 
monitoring and alerting rules. From the SLI's, engineers create well defined and goal oriented SLO's.

