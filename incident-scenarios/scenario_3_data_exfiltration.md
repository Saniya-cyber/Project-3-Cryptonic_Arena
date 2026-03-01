# Incident Scenario 3: Data Exfiltration

## Description

Large outbound data transfer (>5GB) to external IP detected.

## Detection Method

Triggered by Rule 3: Excessive Outbound Data Transfer.

## Severity

Critical

## Response Steps

1. Block external IP address.
2. Identify compromised endpoint.
3. Investigate user activity.
4. Preserve forensic evidence.
5. Notify management.

## Lessons Learned

- Implement DLP (Data Loss Prevention).
- Monitor abnormal outbound traffic.
