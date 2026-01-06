# Enterprise Event-Driven File Replication Architecture

This repository documents a production-grade, event-driven file replication
architecture using Solace as the messaging backbone.

## Architecture Overview
- Application-level file segmentation
- Guaranteed message delivery using PUB/SUB
- Active/Standby HA appliances
- SAN-backed persistent queues
- Forward replication (PROD → DR)
- Reverse replication for DR testing without redeployment

## Key Design Principles
- Event-driven architecture (EDA)
- Decoupled producers and consumers
- High availability with no single point of failure
- Deterministic data movement using cron-based triggers

## Notes
- This is a **conceptual architecture**
- No proprietary configurations or sensitive details are included
- Designed to explain real-world enterprise patterns
