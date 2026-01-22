## Solution Overview

I proposed and contributed to the design of a centralized Vendor Monitoring & Control Portal that provides:

### 1. Centralized Vendor Management

- Secure web portal for authorized technical users

- Ability to:

  - Enable/disable vendors in real time
  
  - Route traffic away from failing vendors

- Eliminates direct database manipulation via SQL scripts

### 2. Real-Time Vendor Performance Monitoring

The portal provides real-time and historical visibility into:

- Daily API call volume per vendor

- Successful vs failed transactions per vendor

- Failure rates and performance trends

- Vendor health indicators

This allows teams to proactively detect degradation before full outages occur.

### 3. Transaction-Level Categorization

All metrics are broken down by:

- Transaction type (e.g., airtime, data, etc.)

- Telco/network operator

- Vendor

This enables:

- Granular root cause analysis

- Identification of vendor-specific or telco-specific issues

- Data-driven vendor performance reviews

### 4. Automated Failover

The system supports automated failover logic, including:

- Automatic routing of transactions to healthy vendors

- Threshold-based vendor isolation

- Reduced dependency on human intervention

- Faster recovery times

This significantly improves system resilience and customer experience.

### 5. SLA Tracking & Vendor Accountability

The portal includes:

- SLA tracking per vendor

- Performance benchmarking

- Trend analysis over time

This supports:

- Vendor governance

- Escalation discussions

- Contractual performance reviews

- Data-backed vendor management decisions

### 6. Real-Time Vendor Escalation Integration

The portal integrates directly with vendor endpoints and escalation channels to:

- Trigger real-time alerts

- Support faster vendor engagement

- Reduce mean time to resolution (MTTR)







