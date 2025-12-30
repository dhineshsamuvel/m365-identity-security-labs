## Objective
Strengthen authentication security using MFA and passwordless authentication.

## Environment
Microsoft Entra ID (Test tenant)

## Configuration Performed
- Enabled Multi-Factor Authentication
- Configured Microsoft Authenticator app
- Enabled passwordless authentication
- Created Temporary Access Pass (TAP)

## Security Rationale
MFA and passwordless authentication reduce the risk of credential theft and phishing attacks.  
Temporary Access Pass provides secure, time-bound access without sharing passwords.

## Outcome
- MFA enforced for user sign-ins
- Passwordless authentication enabled
- Secure temporary access supported

## Validation
Users were required to complete MFA or passwordless authentication during sign-in.

## Interview Talking Points
- MFA vs passwordless
- Authenticator app benefits
- TAP use cases
