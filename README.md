# Azure-Entra-ID-Identity-Lifecycle-Conditional-Access-Lab
## Overview
This lab demonstrates end-to-end identity lifecycle management and 
access control in Microsoft Azure Entra ID. It covers user 
provisioning, access governance, and enforcing Zero Trust principles 
through Conditional Access policies.

---

## Objectives
- Implement joiner/mover/leaver lifecycle workflows in Entra ID
- Configure role-based access control (RBAC) using least-privilege principles
- Enforce MFA and Conditional Access policies
- Conduct access reviews to maintain compliance
- Manage entitlements using Azure AD Entitlement Management

---

## Tools & Technologies
- Microsoft Azure Entra ID (Azure AD)
- Azure Portal
- PowerShell / Microsoft Graph API
- Microsoft Sentinel (logging & monitoring)

---

## Lab Breakdown

### 1. User Lifecycle Management
- Created user accounts simulating onboarding (Joiner)
- Modified group memberships and roles for role changes (Mover)
- Disabled and deprovisioned accounts for offboarding (Leaver)

### 2. Role-Based Access Control (RBAC)
- Assigned built-in roles following least-privilege principles
- Created custom roles scoped to specific resources
- Reviewed and removed excessive permissions

### 3. Conditional Access Policies
- Enforced MFA for all users
- Blocked access from untrusted locations
- Configured risk-based sign-in policies

### 4. Access Reviews
- Configured recurring access reviews for privileged roles
- Automated removal of unused access
- Documented review findings

### 5. Entitlement Management
- Created access packages for department-based access
- Configured approval workflows
- Set access expiration policies

---

## Key Takeaways
- Automating lifecycle management reduces risk from orphaned accounts
- Conditional Access is foundational to Zero Trust architecture
- Regular access reviews enforce least-privilege over time
