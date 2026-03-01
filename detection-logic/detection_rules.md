# Detection Rules & Explanation

## Rule 1: SSH Brute Force Detection

Condition:
If failed login attempts > 5 within 2 minutes from same IP address.

Alert Level:
High

Explanation:
Multiple rapid failed login attempts indicate brute force attempts.

MITRE ATT&CK Mapping:
T1110 - Brute Force

---

## Rule 2: Suspicious Successful Login After Failures

Condition:
Multiple failed login attempts followed by successful login.

Alert Level:
Critical

Explanation:
Indicates possible credential compromise.

MITRE ATT&CK Mapping:
T1078 - Valid Accounts

---

## Rule 3: Excessive Outbound Data Transfer

Condition:
Outbound data transfer > 2GB within 10 minutes.

Alert Level:
Critical

Explanation:
May indicate data exfiltration activity.

MITRE ATT&CK Mapping:
T1041 - Exfiltration Over Command and Control Channel

---

## Rule 4: Repeated HTTP 401 Responses

Condition:
More than 3 HTTP 401 responses from same IP within 1 minute.

Alert Level:
Medium

Explanation:
Possible web login brute force or credential stuffing.
