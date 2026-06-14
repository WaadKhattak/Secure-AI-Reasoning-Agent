# Secure Threat Intelligence Assistant (Sentinel-IQ)

An autonomous cybersecurity reasoning agent built for the Microsoft Agents League Hackathon 2026.

## Overview
Sentinel-IQ combines multi-step reasoning architectures with **Microsoft Foundry IQ** concepts to analyze incoming cyber threats, bypass prompt-injection attacks, and safely pull grounded enterprise security playbooks to mitigate attacks in real time.

## Rubric Highlights
* **Microsoft IQ Integration:** Leverages simulated **Foundry IQ** layers to fetch specific, high-permission compliance playbooks dynamically, removing LLM hallucinations entirely during an incident response crisis.
* **Reasoning & Multi-step Thinking:** Implements strict chain-of-thought steps prompting the agent to categorize, verify, and resolve anomalies sequentially.
* **Reliability & Safety:** Includes an automated input interception guardrail to block exploit payloads and prompt injection attempts from hijacking the agentic workflow.

##  How to Run
1. Clone the repository.
2. Execute the script: `python agent.py`
  
