Praetorian is a high-performance C++17/20 framework implementing battle-tested resilience patterns for distributed systems.
It’s designed as both a learning playground and a production-grade library, with a built-in load simulator and observability stack.

📜 Overview

This project re-implements foundational reliability mechanisms from scratch in modern C++, with a focus on lock-free concurrency, metrics instrumentation, and chaos testing.

- Planned patterns include:
- Exponential Backoff (with jitter strategies)
- Throttling (concurrency limits)
- Back Pressure (bounded queues + drop policies)
- Rate Limiting (token bucket)
- Circuit Breakers (sliding window, half-open probes)
- Bulkhead Pattern (workload isolation)
- At-Least-Once Delivery (idempotent deduplication)
- Blue-Green Deployments (zero downtime cutover)
- Canary Deployments (weighted rollout + auto rollback)
- SLI/SLO/SLA monitoring
- RED Metrics (Rate, Errors, Duration)
