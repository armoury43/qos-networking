# QoS Networking

> A visual and practical guide to Quality of Service (QoS) in computer networks.

## Overview

Network traffic is not equally sensitive to delay, jitter, packet loss, or bandwidth limitations.

Quality of Service (QoS) provides mechanisms for identifying and managing different types of traffic so that latency-sensitive applications can receive appropriate treatment when network resources are under contention.

This repository explains QoS through practical examples, network diagrams, and real-world scenarios.

## What You'll Learn

- Traffic Classification
- Traffic Marking
- Queuing
- Scheduling
- Priority Handling
- Congestion Management
- Traffic Shaping
- Traffic Policing
- Latency & Jitter
- Packet Loss
- DSCP

## Real-World Traffic

| Traffic | Main Concern |
|---|---|
| VoIP | Latency, jitter, packet loss |
| Video | Bandwidth, latency |
| Web | Response time |
| File Transfer | Bandwidth |

## Repository Structure

```text
qos-networking/
├── README.md
├── docs/
│   ├── fundamentals.md
│   ├── traffic-management.md
│   └── real-world-examples.md
└── diagrams/