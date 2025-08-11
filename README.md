# Mixed-Criticality-Digital-Cockpit
Project utilizing QNX Hypervisor hosting Real Time OS (Linux) and Non Critical Infotainment OS (Android)

# Overview
This blueprint details the design and implementation of a mixed-criticality digital cockpit. The system will consolidate multiple functions with varying safety integrity levels onto a single System-on-a-Chip (SoC) using virtualization. The primary architecture will utilize the QNX Hypervisor as a Type 1 hypervisor, hosting a safety-critical Linux-based instrument cluster and a non-safety-critical Android-based infotainment system. The project's core objective is to demonstrate the safe and secure isolation of these two domains while enabling efficient communication between them for a cohesive user experience.
