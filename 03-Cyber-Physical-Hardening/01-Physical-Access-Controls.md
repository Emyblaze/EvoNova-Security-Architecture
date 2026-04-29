# Physical Access Controls for Edge Nodes

**Status:** Draft / Outline

## The Core Premise
While enterprise data centers are protected by armed guards and biometric scanners, edge nodes—such as localized routers, industrial control systems, and smart inverters—are often deployed in highly accessible, low-security environments. If an attacker can physically touch the device, they own the device.

## Key Arguments to Develop:
1. **Anti-Tamper Mechanisms:** Implementing chassis intrusion detection, tamper-evident seals, and hardware kill-switches for remote deployments.
2. **Port Security at the Bare Metal:** The necessity of physically disabling or locking unused serial, console, and USB ports to prevent rogue "Rubber Ducky" style attacks or direct console access.
3. **Environmental Sabotage:** Hardening the localized power and cooling supplies of edge nodes to prevent attackers from forcing system reboots or causing thermal shutdowns to bypass fail-safe protocols.

## Operational Playbook
*Outline pending: A standardized physical security audit checklist for deploying hardware outside of controlled data centers.*
