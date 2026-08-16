# Auto-Scaling Web Application Cluster (Azure)

## Overview
This project implements a scalable web application using Azure Virtual Machine Scale Sets (VMSS) with automated scaling rules based on CPU utilization.

## Architecture Diagram
<img width="1042" height="692" alt="Azure lab 3" src="https://github.com/user-attachments/assets/323616f7-ab00-4ba1-a362-85b06bd443ba" />

**Diagram components:**
- VM Scale Set (VMSS)
- Load Balancer
- Custom Script Extension (Nginx/IIS)
- Autoscale Rules

## Azure Services Used
- Virtual Machine Scale Sets
- Azure Load Balancer
- Azure Monitor (Autoscale)
- Custom Script Extensions

## Implementation Steps
1. Deploy a VMSS with Ubuntu or Windows Server.
2. Configure a Custom Script Extension to install Nginx/IIS.
3. Set autoscale rules: scale out when CPU > 70%, scale in when < 30%.
4. Validate scaling behavior under simulated load.

## Best Practices Learned
- Autoscaling optimizes cost and performance.
- Custom scripts automate consistent configuration.
- Load balancing ensures high availability.
