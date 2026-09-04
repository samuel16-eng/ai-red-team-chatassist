# NVIDIA Garak Scan Results

## Purpose

This directory documents the setup, execution, and sanitized results of automated LLM vulnerability scans performed with Garak.

## Current Status

- Garak installation: Verified
- Garak version: `0.9.0.11.post1`
- Operating system: macOS
- Target model: Not yet selected
- Vulnerability scan: Pending

Running `garak --version` confirmed that the tool was installed successfully. This verification does not represent a completed security scan.

## Planned Testing Process

1. Select an authorized test model
2. Configure the required environment variables
3. Select relevant Garak probes
4. Execute the scan
5. Review detector results
6. Remove secrets and sensitive information
7. Document findings and supporting evidence

## Scan Record Template

| Field | Value |
|---|---|
| Scan date | Pending |
| Garak version | 0.9.0.11.post1 |
| Target model | Pending |
| Probe categories | Pending |
| Total tests | Pending |
| Passed tests | Pending |
| Failed tests | Pending |
| Primary finding | Pending |

## Evidence Handling

Only sanitized results will be published. API keys, authentication tokens, personal information, and confidential course materials will not be committed to this repository.

## Important Interpretation

A Garak detector failure indicates behavior requiring manual review. It does not automatically prove that the target model contains an exploitable production vulnerability.
