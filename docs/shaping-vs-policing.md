# Traffic Shaping vs Policing

Traffic shaping and traffic policing are both used to control traffic rates, but they handle excess traffic differently.

## Traffic Shaping

Shaping controls the rate at which traffic is transmitted.

When traffic temporarily exceeds the configured rate, packets can be buffered and transmitted later.

```text
Burst Traffic
      |
      v
+-------------+
|   Shaper    |
+-------------+
      |
      v
Controlled Traffic Rate
