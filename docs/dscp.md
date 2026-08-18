# DSCP

Differentiated Services Code Point (DSCP) is a 6-bit field used in the IP header to classify packets for differentiated treatment.

## Where DSCP Exists

DSCP is carried in the IP header as part of the Differentiated Services (DS) field.

```text
IPv4

+--------+--------+--------+--------+
| Version|  IHL   | DSCP   |  ECN   |
+--------+--------+--------+--------+
