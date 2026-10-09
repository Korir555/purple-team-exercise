# Purple Team Exercise

Red and blue team collaboration framework demonstrating coordinated attack simulation, detection, response, and post-incident analysis. Showcases mature security operations with attack/defense balance.

## Overview

Purple team exercise combining red team attacks with blue team defenses in a controlled environment. Demonstrates collaborative security operations: attack execution, real-time detection, incident response, and lessons learned capture.

## Key Features

- **Red Team Scenarios**: Multi-stage attacks (reconnaissance, initial access, persistence, exfiltration)
- **Blue Team Defenses**: Detection rules, response procedures, incident containment
- **Live Exercise**: Simulated attacks with real-time monitoring and response
- **Detection Engineering**: Alert rules, log correlation, threat detection optimization
- **Incident Response Playbooks**: Step-by-step response procedures
- **Lessons Learned**: Post-exercise analysis, findings, recommendations

## Key Components

- Attack scenario definitions (initial compromise through impact)
- Detection signatures and correlation rules
- Blue team response procedures and runbooks
- Real-time dashboard for attack/defense tracking
- Post-exercise debriefing and findings analysis
- Metrics: detection latency, response time, containment success

## Exercise Scenarios

- **Multi-stage APT Simulation**: Reconnaissance → Initial Access → Persistence → Exfiltration
- **Lateral Movement**: Cross-system compromise and privilege escalation
- **Evasion Techniques**: Anti-forensics, log deletion, process injection
- **Command & Control**: C2 beaconing and data exfiltration

## Installation

```bash
git clone https://github.com/Korir555/purple-team-exercise.git
cd purple-team-exercise
pip install -r requirements.txt
```

## Technologies

Python 3.9+, Bash, YARA, Suricata, Wazuh, Linux

## Hiring Relevance

- Red and blue team collaboration
- Incident response under pressure
- Detection engineering
- Real-world attack/defense scenarios
- Security operations maturity
- Post-incident analysis capability
- Safaricom/Equity SOC experience alignment
