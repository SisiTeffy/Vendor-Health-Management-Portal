## System Architecture (High-Level)

### Core Components:

- Vendor Monitoring Service

  - Collects transaction metrics and API health data

- Vendor Control Service

  - Manages vendor enable/disable states
  
  - Handles failover logic

- Analytics & Reporting Layer

  - Aggregates success/failure trends
  
  - SLA calculations

- Web-Based Admin Portal

  - Role-based access control
  
  - Real-time dashboards
  
  - Vendor management controls

- Vendor Integration Layer

  - API connectivity
  
  - Escalation hooks
  
  - Health check endpoints
  
## High-Level Flow:

1. Transactions are routed through the integration layer

2. Metrics are captured in real time

3.Health status is evaluated continuously  

4.Failover rules are applied automatically when thresholds are breached

5.Portal dashboards update in real time

6.Authorized users can manually override or investigate when needed



