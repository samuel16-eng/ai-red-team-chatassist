# AI Red Team Assessment – ChatAssist

## Overview

This portfolio project documents a security assessment of ChatAssist, a simulated customer-facing chatbot. The assessment follows an AI red-team workflow combining manual attack design with automated vulnerability scanning using NVIDIA Garak.

## Objectives

- Identify prompt injection and jailbreak vulnerabilities
- Test for sensitive information disclosure
- Evaluate potentially unsafe model behavior
- Document reproducible attack scenarios and evidence
- Assess risk severity and business impact
- Recommend mitigations and a launch decision

## Assessment Workflow

1. Define the threat model
2. Design adversarial attack scenarios
3. Run automated Garak scans
4. Analyze and prioritize findings
5. Recommend security improvements
6. Make a launch or delay recommendation

## Repository Structure

- `threat-model/` — assets, attack surfaces, threats, and risks
- `attack-scenarios/` — manually designed adversarial tests
- `garak-results/` — sanitized automated scan results
- `findings/` — vulnerabilities, evidence, and severity ratings
- `remediation/` — recommended mitigations and security controls

## Tools

- NVIDIA Garak
- Python
- macOS Terminal
- Git and GitHub

## Status

Work in progress. Findings and recommendations will be added as the assessment proceeds.

## Security Notice

No API keys, private customer data, or confidential course materials are included in this repository.

## Skills Demonstrated

- AI threat modeling and attack-surface analysis
- Structured adversarial prompt design
- Vulnerability classification and severity assessment
- Reproducible security documentation
- Business-impact analysis
- Remediation planning and launch-risk evaluation
- Clear communication for technical and non-technical stakeholders

## Project Navigation

- [Threat Model](threat-model/README.md)
- [Attack Scenarios](attack-scenarios/README.md)
- [Garak Results](garak-results/README.md)
- [Security Findings](findings/README.md)
- [Remediation Recommendations](remediation/README.md)
