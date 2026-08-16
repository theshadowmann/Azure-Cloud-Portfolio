# Secure Static Asset Pipeline & Hybrid Storage (Azure)

## Overview
This project demonstrates secure cloud storage and hybrid file sharing using Azure Blob Storage and Azure Files.  
It simulates a real-world scenario where a business hosts public website assets while maintaining private internal file access.

**Diagram components:**
- Storage Account (LRS or GRS)
- $web container for static site hosting
- SAS token for temporary upload access
- Azure Files share mounted locally

## Azure Services Used
- Azure Storage (Blob & File)
- Shared Access Signatures (SAS)
- Microsoft Entra ID authentication
- Private Endpoints (optional)

## Implementation Steps
1. Create a Storage Account with LRS redundancy.
2. Enable static website hosting and upload `index.html` to `$web`.
3. Generate a SAS token with limited permissions and expiration.
4. Create an Azure Files share and mount it locally via SMB.

## Best Practices Learned
- Use SAS tokens for time-limited access instead of exposing keys.
- Separate public and private assets using containers and shares.
- Apply network restrictions and private endpoints for sensitive data.
authentication.”

