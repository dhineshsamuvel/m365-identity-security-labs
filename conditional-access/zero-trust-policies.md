## Objective
Enforce Zero Trust access control using Conditional Access policies.

## Environment
Microsoft Entra ID (Test tenant)

## Configuration Performed
- Required MFA using Conditional Access
- Blocked legacy authentication
- Restricted access outside India
- Required compliant devices for access

## Security Rationale
Conditional Access evaluates identity, device, and context before granting access.  
Blocking legacy authentication prevents MFA bypass and reduces attack surface.

## Outcome
- Legacy authentication blocked
- Access restricted by location and device compliance
- MFA enforced through policy

## Validation
Sign-in behavior reflected Conditional Access enforcement.

## Interview Talking Points
- Conditional Access vs per-user MFA
- Why legacy authentication is risky
- Device compliance in Zero Trust
