# USB Baiting Attack Analysis

## Overview

This project analyzes the security risks associated with USB baiting attacks and removable media exposure in a healthcare environment.

The investigation focuses on attacker mindset analysis, sensitive information exposure, social engineering risks, and security controls related to unidentified USB devices discovered in a workplace parking lot.

---

## Scenario

A USB drive labeled with the hospital logo was discovered in the parking lot of Rhetorical Hospital. The USB contained a combination of personal and work-related files belonging to a hospital employee.

The device was safely examined inside a virtualized environment to reduce the risk of malware execution and unauthorized network access.

---

## USB Drive Evidence

![USB Drive Contents](usb-drive-preview.png)

---

## Objectives

- Analyze sensitive information stored on removable media
- Evaluate attacker techniques involving USB baiting
- Identify operational and technical security risks
- Examine social engineering attack vectors
- Recommend mitigations against removable media attacks

---

## Key Security Concepts

- USB Baiting
- Social Engineering
- Malware Delivery
- Insider Threat Awareness
- Removable Media Security
- Least Privilege
- Operational Security
- Virtualization and Sandboxing

---

## Key Findings

- The USB drive contained both personal and work-related files.
- Sensitive business documents and employee-related information were exposed.
- Mixing personal and corporate data increased organizational risk exposure.
- A malicious actor could potentially use the files for phishing, impersonation, or malware delivery attacks.
- Virtualization software helped safely isolate the investigation environment.

---

## Repository Structure

- `contents-analysis.md`
- `attacker-mindset.md`
- `risk-analysis.md`

Supporting documentation is stored in the `docs/` directory.

---

## References

- [Parking Lot USB Exercise Template](docs/parking-lot-usb-exercise.pdf)
- [USB Drive Evidence Screenshot](usb-drive-preview.png)
- USB baiting attack awareness concepts
- Removable media security best practices
