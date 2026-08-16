# Two-Tier Isolated Virtual Network Architecture (Azure)

## Overview
This project builds a secure two-tier network topology separating public web servers from private database servers using VNets and NSGs.

**Diagram components:**
- Virtual Network (10.0.0.0/16)
- FrontendSubnet (10.0.1.0/24)
- BackendSubnet (10.0.2.0/24)
- NSG rules restricting inbound traffic
- Load Balancer for frontend VMs

## Azure Services Used
- Virtual Networks & Subnets
- Network Security Groups (NSGs)
- Azure Load Balancer
- Public IPs

## Implementation Steps
1. Create a VNet with two subnets.
2. Deploy web and database VMs in separate subnets.
3. Configure NSG rules to allow traffic only from frontend to backend.
4. Add a Load Balancer to distribute web traffic.

## Best Practices Learned
- Network segmentation enhances security.
- NSGs enforce least-privilege access.
- Load balancing improves reliability.
