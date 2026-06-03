## Overview
This lab demonstrates a complete security operations workflow: attack simulation → network detection → SIEM alerting → packet analysis → incident investigation.

## Architecture
Attacker (nmap/hydra) → Suricata IDS → Wazuh SIEM → Wireshark → Investigation Report

## Tools Used
| Tool | Purpose |
|------|---------|
| Wazuh | SIEM — log collection, alerting, dashboard |
| Suricata | Network IDS — traffic monitoring, rule-based detection |
| Wireshark | Packet analysis — deep traffic inspection |
| Nmap | Network scanning simulation |
| Hydra | Brute force attack simulation |

## Lab Structure

01-environment-setup/    # Ubuntu VM configuration
02-tool-deployment/      # Tool installation guides
03-attack-simulation/    # Attack scenarios
04-detection-analysis/   # Alert analysis
05-investigations/       # Incident response case studies
screenshots/             # Evidence and screenshots

## Key Scenarios
- Brute force SSH detection via Wazuh
- Network scanning detection via Suricata
- Suspicious process monitoring
- Packet-level investigation with Wireshark

## Skills Demonstrated
- SIEM deployment and alert tuning
- Network intrusion detection
- Log analysis and correlation
- Attack simulation
- Incident investigation workflow
- Technical documentation

## Status
🚧 Lab in progress — tools deployed, attack simulation phase starting.

## Author
Idowu adewale — SOC Analyst | Detection Engineering
