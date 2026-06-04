Overview
This lab demonstrates a complete security operations workflow,covering the full lifecycle of cyber threat detection and response:

attack simulation → network detection → SIEM alerting → packet analysis → incident investigation.

It showcases how security events are identifired,validated, and documneted.

Architecture
Attack Simulation (Nmap / Hydra)
→ Network Detection (Suricata)
→ Log Correlation & Alerting (Wazuh)
→ Packet Analysis (Wireshark)
→ Incident Investigation & Reporting
→ Detection Engineering (Sigma rules)

| Tool      | Purpose                                                              |
| --------- | -------------------------------------------------------------------- |
| Wazuh     | SIEM — log collection, alerting, correlation, and dashboard analysis |
| Suricata  | Network IDS — traffic inspection and signature-based detection       |
| Wireshark | Packet analysis — deep inspection of network traffic                 |
| Nmap      | Network reconnaissance simulation                                    |
| Hydra     | Authentication brute force simulation                                |


## Lab Structure
01-environment-setup/     Ubuntu VM configuration

02-tool-deployment/       Tool installation guides

03-attack-simulation/     Attack scenarios

04-detection-analysis/    Alert analysis (Wazuh + Suricata)

05-investigations/        Incident response case studies

06-detection-engineering  Sigma rules and detection logic 

screenshots/              Evidence and screenshots

 Key Scenarios
- Brute force SSH detection via Wazuh
- Network scanning detection via Suricata
- Suspicious process monitoring
- Packet-level investigation with Wireshark
- Detection rule development using Sigma methodology
-MITRE ATT&CK mapping of observed behaviour

 Skills Demonstrated
- SIEM deployment and alert tuning
- Network intrusion detection
- Log analysis and correlation
- Attack simulation
- Incident investigation workflow
- Technical documentation
- Packet-level forensic analysis
-Detection engineering and rule creation (Sigma)
-MITRE ATT&CK-based threat mapping
-Structured incident documentation and reporting

Status
 Active development — currently in the attack simulation and investigation phase, with detection engineering (Sigma rules) being integrated.

Author
Idowu adewale — inspiring  SOC Analyst 
