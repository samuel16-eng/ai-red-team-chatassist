# Threat Model – ChatAssist

## 1. System Overview

ChatAssist is a simulated customer-facing chatbot designed to handle customer inquiries, account lookups, and product recommendations. The system is expected to serve approximately 500,000 customers.

## 2. Security Objectives

The assessment focuses on protecting:

- Customer personal and account information
- Authentication and session data
- Internal system instructions
- Connected business systems and APIs
- Conversation logs
- The reliability and reputation of the organization

## 3. Potential Threat Actors

- Unauthenticated external users
- Authenticated customers attempting unauthorized access
- Attackers using automated or repeated prompts
- Users attempting to manipulate the chatbot’s instructions
- Insiders with inappropriate access to chatbot data or logs

## 4. Attack Surfaces

- User messages and multi-turn conversations
- Account lookup functions
- Product recommendation functions
- System prompts and hidden instructions
- Connected APIs and external data sources
- Conversation history and stored logs

## 5. Primary Threats

| Threat | Potential Impact | Priority |
|---|---|---|
| Sensitive information disclosure | Exposure of customer or internal data | Critical |
| Authorization bypass | Access to another customer’s account information | Critical |
| Prompt injection | Manipulation of chatbot instructions or connected tools | High |
| Jailbreak and policy evasion | Generation of restricted or unsafe responses | High |
| System prompt leakage | Disclosure of internal rules and configurations | Medium |
| Hallucinated information | Incorrect account or product information | High |
| Automated abuse | Large-scale probing or repeated attacks | Medium |

## 6. Trust Boundaries

A trust boundary exists whenever information moves between components with different levels of trust:

1. Customer to ChatAssist
2. ChatAssist to the language model
3. Language model to account or product systems
4. ChatAssist to conversation logs and monitoring systems

All user-provided input must be treated as untrusted.

## 7. Assessment Scope

This project evaluates the chatbot through:

- Manual adversarial scenarios
- Automated vulnerability scanning with NVIDIA Garak
- Review of model responses
- Risk severity and business-impact analysis
- Remediation and launch-readiness recommendations

## 8. Assumptions and Limitations

This is a simulated portfolio assessment based on a training scenario. It does not test a real production system or use real customer information.
