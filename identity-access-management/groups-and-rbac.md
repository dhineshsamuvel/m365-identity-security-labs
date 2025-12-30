## Objective
Implement group-based access control and role-based administration in Microsoft Entra ID.

## Environment
Microsoft Entra ID (Test tenant)

## Configuration Performed
- Created Microsoft 365 Groups
- Created Security Groups
- Created Dynamic Groups
- Reviewed built-in admin roles:
  - Global Administrator
  - Security Administrator
  - Helpdesk Administrator

## Security Rationale
Groups simplify access management and reduce manual permission assignment.  
RBAC ensures administrative privileges are assigned based on responsibility, reducing excessive privilege exposure.

## Outcome
- Access was managed centrally using groups
- Administrative roles were clearly separated
- Reduced dependency on individual permissions

## Validation
Group membership and role assignments were visible and enforceable in Entra ID.

## Interview Talking Points
- Microsoft 365 Group vs Security Group
- Dynamic Group use cases
- Why Global Admin should be limited
