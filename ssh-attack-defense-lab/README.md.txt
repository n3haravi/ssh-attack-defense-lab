# SSH Attack–Defense Lab (Linux)

## Overview
This project simulates a real-world SSH brute-force attack against a Linux server and demonstrates how proper SSH hardening prevents credential-based attacks.

The lab was built using two virtual machines:
- Kali Linux (Attacker)
- Debian Linux (Defender)

---

## Threat Model
- Attack Vector: SSH brute-force using Hydra
- Target: OpenSSH service on Debian
- Goal: Prevent credential-based compromise

---

## Attack Simulation
- Attempted SSH brute-force using Hydra
- Observed authentication failures and connection resets
- Identified why password-based attacks failed

---

## Defensive Measures
- SSH key-based authentication
- Password authentication effectively disabled
- Log analysis using `journalctl`

---

## Evidence
- SSH authentication logs
- Failed brute-force attempts
- Verified secure SSH access using keys

---

## Key Learnings
- Why brute-force attacks fail on hardened systems
- Importance of authentication vs authorization
- Real-world SSH defense behavior

---

## Tools Used
- Kali Linux
- Debian Linux
- OpenSSH
- Hydra
