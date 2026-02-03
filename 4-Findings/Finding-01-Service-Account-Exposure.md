# Finding 01 – Service Account Kerberos Exposure

## Severity
High

## Description
The SVC-WEB account was configured with an SPN and
a non-expiring password.

## Business Impact
Compromise of this account could enable internal
privilege escalation and lateral movement.

## Recommendation
- Use managed service accounts
- Enforce password rotation
- Audit SPNs regularly
