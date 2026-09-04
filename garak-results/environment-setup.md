# Garak Environment Setup

## Purpose

This document records the local environment used to prepare for automated LLM security testing. It supports reproducibility and distinguishes installation verification from an actual vulnerability scan.

## Environment

| Component | Value |
|---|---|
| Operating system | macOS |
| Interface | Terminal |
| Security scanner | Garak 0.9.0.11.post1 |
| Local model runtime | Ollama 0.33.2 |
| Target model | Not yet selected |
| Scan status | Pending |

## Completed Setup Checks

- Apple Command Line Tools were installed and activated
- Garak was installed successfully
- The Garak command-line interface launched successfully
- Ollama was installed and its version was verified

## Verification Commands

- `python3 --version` — confirms that Python is available
- `xcode-select --print-path` — confirms that the macOS Command Line Tools are active
- `python3 -m pip show garak` — displays the installed Garak package information
- `garak --version` — confirms that Garak can launch successfully
- `ollama --version` — confirms that the local model runtime is available

## Pending Steps

- Select and install an authorized local test model
- Connect Garak to the local model
- Select relevant Garak probes
- Run the vulnerability scan
- Review and sanitize the generated outputs
- Record verified findings

## Credential Security

API keys and authentication tokens must never be written directly into scripts, screenshots, reports, or GitHub files. A local Ollama model may allow testing without exposing a paid API key.

## Interpretation

Successful execution of `garak --version` proves that the scanner is installed. It does not prove that a model has been scanned or that a vulnerability has been identified.
