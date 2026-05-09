# Basic SOC Investigation Flow

```text
+------+       +------+       +------+       +--------+       +---------+       +---------------+
| User | --->  | Logs | --->  | SIEM | --->  | Alert  | --->  | Analyst | --->  | Investigation |
+------+       +------+       +------+       +--------+       +---------+       +---------------+
```

## Description

This diagram represents a basic Security Operations Center (SOC) workflow.

1. A user performs activity on a system.
2. Logs are generated from that activity.
3. The SIEM collects and analyzes the logs.
4. Suspicious activity triggers an alert.
5. A SOC analyst reviews the alert.
6. An investigation begins to determine whether the activity is malicious.
