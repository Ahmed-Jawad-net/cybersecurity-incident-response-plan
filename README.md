# Cybersecurity Incident Response Plan — Ransomware Simulation & Staff Training

**Internee.pk Cybersecurity Internship — Task Submission**
Author: Jawad Ahmed

## Overview

This repository contains a structured Incident Response (IR) plan built around the NIST SP 800-61 lifecycle (Preparation → Detection & Analysis → Containment/Eradication/Recovery → Post-Incident Activity). It includes:

- Documented procedures for threat detection, mitigation, and recovery
- A ransomware attack **tabletop simulation** run in an isolated lab environment, mapped to the MITRE ATT&CK framework
- A staff training and awareness program for emergency response protocols

> **Note on the simulation:** No real ransomware or malicious payload was used. The exercise uses a benign, purpose-built test script that only renames files inside an isolated test folder, to safely rehearse the detection → containment → recovery workflow without any risk to real systems.

## Repository Contents

```
├── README.md                          # This file
├── Incident_Response_Plan.docx        # Full IR plan (procedures, MITRE mapping, training plan)
├── incident-log-template.md           # Blank fill-in template used during the tabletop exercise
└── mitre-attack-mapping.md            # MITRE ATT&CK technique mapping for the simulated attack chain
```

*(Adjust the file list above to match whatever you actually upload — see "What to Upload" below.)*

## Framework Used

- **NIST SP 800-61** — Computer Security Incident Handling Guide (four-phase lifecycle)
- **MITRE ATT&CK** — technique mapping for the simulated ransomware attack chain (Initial Access → Execution → Persistence → Defense Evasion → Impact → Exfiltration)

## Key Sections

| Section | Contents |
|---|---|
| Preparation | Asset inventory, backup strategy, logging, IR roles, severity matrix |
| Detection | Detection sources, triage procedure, escalation path |
| Containment & Eradication | Host isolation, evidence preservation, root-cause removal |
| Recovery | Safe restoration procedure, staged reconnection, credential resets |
| Post-Incident | Lessons-learned process, control improvement tracking |
| Ransomware Simulation | Tabletop exercise setup, MITRE mapping, step-by-step walkthrough, incident log |
| Staff Training | Four training modules, rollout schedule, effectiveness metrics |

## Disclaimer

This is an educational/internship deliverable prepared for a controlled lab environment. It does not contain, reference, or link to any real malware, exploit code, or production system data.
