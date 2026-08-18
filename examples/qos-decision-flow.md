# QoS Decision Flow

This example shows a simplified decision process for handling network traffic.

## Flow

```text
Incoming Packet
      |
      v
+----------------+
| Classification |
+----------------+
      |
      v
+----------------+
|    Marking     |
+----------------+
      |
      v
+----------------+
| Queue Selection|
+----------------+
      |
      v
+----------------+
|   Scheduling   |
+----------------+
      |
      v
+----------------+
| Shaping /      |
| Policing       |
+----------------+
      |
      v
Transmission
