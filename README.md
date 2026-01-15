# SOC Detections

High-quality detection rules and threat hunting content for Security Operations Centers (SOC).
This repository focuses on **real-world attacker techniques**, not academic examples.

## Coverage
- Sigma rules (Windows, Linux, Cloud)
- YARA rules for malware and webshell detection
- Network detections (Suricata, Snort)
- Detection ideas mapped to MITRE ATT&CK
- Test data for validation and tuning

## Design Principles
- False-positive aware
- SOC-validated logic
- Based on real incidents and campaigns
- SIEM-friendly and production-oriented

## Supported Platforms
- Elastic Security
- Splunk
- Microsoft Sentinel
- QRadar (via Sigma conversion)

## Repository Structure
- sigma/ → Host-based detections
- yara/ → File and memory detection
- suricata/ → Network IDS rules
- snort/ → Network IDS rules
- test-data/ → Sample logs, payloads, PCAPs

## Testing & Validation
Rules are tested using:
- Atomic Red Team
- Custom lab simulations
- Public malware datasets
- Sigma validation tooling

## MITRE ATT&CK
Each detection includes:
- Technique ID
- Tactic
- Clear detection logic
- Known false positives

## Contributions
Contributions are welcome.
Please read `CONTRIBUTING.md` before submitting pull requests.

## Disclaimer
These rules are provided for defensive purposes only.
Always test in a controlled environment before deploying to production.

  
