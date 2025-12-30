## Objective
Manage and secure the user identity lifecycle in Microsoft Entra ID.

## Environment
Microsoft Entra ID (Test tenant)

## Configuration Performed
- Created cloud-only user accounts
- Assigned Microsoft 365 licenses to users
- Reset user passwords
- Blocked and unblocked user sign-ins
- Verified user account status and access eligibility

## Security Rationale
Controlling the user lifecycle ensures that only authorized and active users can access organizational resources.  
Blocking sign-ins allows immediate response to compromised or inactive accounts without deleting identities.

## Outcome
- Users were successfully provisioned and licensed
- Access was controlled using sign-in state
- Identity hygiene was maintained

## Validation
Users could access services when enabled and were denied access immediately when sign-in was blocked.

## Interview Talking Points
- Block sign-in vs delete user
- License assignment best practices
- Role of sign-in blocking in incident response
