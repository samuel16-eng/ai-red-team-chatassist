# Security Findings – ChatAssist

## Purpose

This directory documents security and safety findings identified during the ChatAssist assessment. Each finding must include reproducible evidence, risk analysis, and a recommended mitigation.

## Current Status

No vulnerabilities have been confirmed yet. Findings will only be added after automated results have been manually reviewed and reproduced where possible.

## Validation Standard

A scanner alert is not automatically treated as a confirmed vulnerability. Before publication, each potential finding should be:

1. Reviewed manually
2. Reproduced where possible
3. Checked for false positives
4. Assessed for customer and business impact
5. Assigned an appropriate severity rating

## Severity Framework

| Severity | Definition |
|---|---|
| Critical | Could expose sensitive customer data or enable unauthorized account access |
| High | Could bypass major safety controls or cause significant customer or business harm |
| Medium | Has limited impact or requires specific conditions to succeed |
| Low | Has minor impact and does not expose sensitive data or critical functionality |
| Informational | Useful security observation without a directly exploitable weakness |

## Finding Template

### Finding ID: F-XX

- **Title:** Pending
- **Status:** Potential / Confirmed / Resolved
- **Category:** Pending
- **Severity:** Pending
- **Affected component:** Pending
- **Related scenario:** Pending
- **Related Garak probe:** Pending

#### Description

Describe the observed behavior and why it represents a security or safety concern.

#### Reproduction Summary

Document the authorized testing conditions and the minimum steps required to reproduce the behavior.

#### Expected Behavior

Describe how the chatbot should have responded securely.

#### Actual Behavior

Describe what the chatbot returned during testing.

#### Evidence

Include sanitized output excerpts, screenshots, or scan references without exposing API keys or sensitive information.

#### Impact

Explain the possible effect on customers, business operations, legal compliance, or organizational reputation.

#### Recommended Mitigation

Describe the control or system change that could reduce the risk.

#### Retest Result

Record whether the mitigation successfully resolved the finding.

## Reporting Principle

All findings must be evidence-based. Unverified scanner alerts and theoretical risks should be clearly labeled and must not be presented as confirmed vulnerabilities.
