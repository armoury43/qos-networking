# QoS Fundamentals

Quality of Service (QoS) is a set of techniques used to manage network traffic when multiple flows compete for limited resources.

## Why QoS Exists

Not all traffic has the same requirements.

Real-time applications such as voice and interactive video are usually more sensitive to:

- Latency
- Jitter
- Packet loss

Other traffic, such as large file transfers, can often tolerate additional delay.

QoS allows the network to treat different traffic classes according to their requirements.

## The QoS Process

A typical QoS workflow can include:

1. **Classification** — Identify the type or class of traffic.
2. **Marking** — Add a traffic classification value such as DSCP.
3. **Queuing** — Place packets into appropriate queues during congestion.
4. **Scheduling** — Determine which queued packets are transmitted next.
5. **Shaping** — Smooth traffic by controlling its transmission rate.
6. **Policing** — Enforce a traffic rate by measuring and potentially dropping or remarking packets.

## Key Performance Factors

### Latency

The time required for traffic to travel from source to destination.

### Jitter

Variation in packet delay over time.

### Packet Loss

Packets that fail to reach their destination.

### Bandwidth

The capacity available for transmitting data.

## Important Principle

QoS does **not** create additional bandwidth.

Instead, it manages the available capacity and determines how competing traffic should be treated, especially during congestion.

## Example

Consider a link carrying:

```text
VoIP
Video
Web Traffic
File Transfer
