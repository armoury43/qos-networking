# VoIP Priority Scenario

## Scenario

A company uses the same WAN connection for:

- VoIP
- Video conferencing
- Web traffic
- File transfers

Voice traffic is particularly sensitive to delay, jitter, and packet loss.

## Traffic Flow

```text
VoIP
  ↓
Classification
  ↓
DSCP Marking
  ↓
Priority Queue
  ↓
Scheduler
  ↓
WAN Link
