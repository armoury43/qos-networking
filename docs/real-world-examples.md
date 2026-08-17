# Real-World QoS Examples

QoS becomes especially useful when different applications compete for the same network resources.

## VoIP

Voice traffic is sensitive to:

- Latency
- Jitter
- Packet loss

QoS can prioritize voice traffic to help maintain a consistent call experience.

## Video

Real-time video requires relatively stable bandwidth and low delay.

QoS can help prevent other traffic from consuming resources needed by video streams.

## Web Traffic

Web requests usually tolerate more delay than real-time voice or video.

They can therefore receive a lower priority when network resources are congested.

## File Transfers

Large file transfers can consume significant bandwidth.

QoS policies can limit or deprioritize this traffic when more latency-sensitive applications need the available capacity.

## Important Note

QoS does not create additional bandwidth.

It controls how available network resources are managed when traffic competes for them.