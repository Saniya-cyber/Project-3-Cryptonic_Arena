# Incident Scenario 1: SSH Brute Force Attack

## Description

Multiple failed SSH login attempts were detected from IP 192.168.1.25, followed by a successful login as root.

## Detection Method

Triggered by:
- Rule 1: Brute Force Detection
- Rule 2: Suspicious Successful Login

## Severity

High

## Response Steps

1. Block malicious IP in firewall.
2. Disable compromised account.
3. Force password reset.
4. Enable Multi-Factor Authentication.
5. Conduct full log investigation.

## Lessons Learned

- Implement account lockout policy.
- Strengthen password complexity requirements.
