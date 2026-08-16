# Centralized Monitoring & Log Analytics (Azure)

## Overview
This project sets up centralized monitoring and alerting using Azure Monitor, Log Analytics, and Kusto Query Language (KQL).

## Architecture Diagram
<img width="1042" height="692" alt="Azure lab 3" src="https://github.com/user-attachments/assets/b888b279-db85-41cb-8780-35a466605240" />

**Diagram components:**
- Log Analytics Workspace
- Azure Monitor Agent
- Alert Rules & Action Groups
- KQL Queries

## Azure Services Used
- Azure Monitor
- Log Analytics Workspace
- Action Groups
- Kusto Query Language (KQL)

## Implementation Steps
1. Create a Log Analytics Workspace.
2. Connect VMs via Azure Monitor Agent.
3. Write KQL queries to detect high CPU or system errors.
4. Configure alerts and action groups for notifications.

## Best Practices Learned
- Centralized logging simplifies troubleshooting.
- KQL enables powerful data analysis.
- Automated alerts improve incident response time.
