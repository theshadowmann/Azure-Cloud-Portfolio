Here’s your **Project 1 README.md**, written in the same structured, professional format as your other projects:

---

# Governance & RBAC (Azure)

## 📌 Overview
This project demonstrates Azure Governance and Role‑Based Access Control (RBAC) by organizing resources under a subscription and applying policies, locks, and role assignments to enforce secure access management.

## Architecture Diagram
<img width="1067" height="707" alt="image" src="https://github.com/user-attachments/assets/84581765-cc09-4738-aa54-7077b6807b8d" />

**Diagram components:**
- Subscription  
- Resource Group A (Owner, Policy, Resource Lock)  
- Resource Group B (Contributor, Virtual Machine, Reader)  
- RBAC Roles (Admin, Dev, Audit)  
- Role Assignments (User, Group)

## Azure Services Used
- Azure Resource Manager (ARM)  
- Role‑Based Access Control (RBAC)  
- Azure Policy  
- Resource Locks  
- Azure Active Directory (Entra ID)

## Implementation Steps
1. Create an Azure subscription and define resource groups.  
2. Assign roles (Owner, Contributor, Reader) to users and groups.  
3. Apply policies to enforce compliance and governance.  
4. Configure resource locks to prevent accidental deletion or modification.

## Best Practices Learned
- Use RBAC to enforce least‑privilege access.  
- Apply policies at the subscription or resource‑group level for consistency.  
- Implement resource locks for critical assets.  
- Separate roles and responsibilities across teams.
