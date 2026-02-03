# Kerberos Service Exposure

## Observation
A service account (SVC-WEB) was configured with a
Service Principal Name (SPN).

## Risk
SPNs expose Kerberos service tickets that can be
requested by any domain user.

## Impact
If the service account password is weak or unmanaged,
offline password attacks may lead to privilege escalation.

## Evidence
(Screenshots and command output)
