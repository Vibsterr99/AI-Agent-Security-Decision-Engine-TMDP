# AI Agent Security Decision Engine (T-MDP)

A cybersecurity research project exploring cost-aware security controls for AI-agent tool execution. The system combines Windows/Sysmon telemetry, calibrated machine-learning risk scores, rule-based analysis, and LLM-assisted judgment with a Terminating Markov Decision Process (T-MDP) to classify proposed agent actions as **EXECUTE, DEFER, or BLOCK**.

The decision threshold is derived from explicit security and usability costs through value iteration rather than being manually selected.

## My Contribution

As part of the project team, I designed the cybersecurity problem formulation and sandbox environment and co-developed the T-MDP security decision architecture. My work included integrating Windows security telemetry with calibrated risk scoring, evaluating security decision policies, analyzing false-positive and calibration behavior, and assessing rule-, ML-, and LLM-assisted approaches to agent command gating.

> **Scope:** This repository is an offline research sandbox. Experiments replay recorded telemetry and simulate security decisions; it does not intercept or block commands on a live production endpoint.
