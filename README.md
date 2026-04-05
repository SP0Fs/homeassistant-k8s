# Home Assistant

Smart home automation platform.

## Overview

[Home Assistant](https://www.home-assistant.io/) is the central hub for home automation, integrating with lights, sensors, switches, and IoT devices.

## Repository Structure

```
homeassistant-k8s/
├── _namespace.yaml
├── deployment.yaml
├── ingress.yaml
├── service.yaml
└── volume.yaml
```

## Configuration

- Persistent storage for config and data
- Ingress with TLS via cert-manager

## Links

- UI: https://homeassistant.spof.local
- Namespace: `homeassistant`
