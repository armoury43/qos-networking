# Traffic Management

QoS traffic management controls how network traffic is classified, marked, queued, scheduled, shaped, and policed.

## 1. Classification

Classification identifies traffic and assigns it to a traffic class.

Common classification inputs include:

- Source or destination IP
- Protocol
- TCP/UDP port
- Application identity
- Existing DSCP markings
- VLAN or interface information

Example:

```text
VoIP        → Voice
Video       → Video
Web         → Best Effort
File        → Bulk
