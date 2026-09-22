# Hi, I'm Yusuke

I'm an automotive systems engineer focused on **Verification & Validation, MBSE, xIL testing, and AI-assisted engineering** for complex physical/software systems.

I build engineering workflows that connect:

**Requirements → Architecture → Verification → Evidence → Human Judgment**

My current focus is extending this approach from automotive V&V into **AI-native engineering, cloud-connected evidence pipelines, SDV, robotics, and physical AI**.

## Featured Work

### Requirements-to-Evidence AI V&V Workbench

[View the repository](https://github.com/Yusuke-Auto/requirements-to-evidence-ai-vv-workbench)

A synthetic engineering work sample exploring how deterministic validation, LLM-assisted review, and human approval can work together without treating an LLM as an oracle.

Current public evidence includes:

- 12 synthetic AEB-like requirements
- Requirement → Component → Test → Evidence traceability
- 5 intentionally seeded benchmark defects
- 5/5 seeded defects detected in the corrected synthetic benchmark
- 1 valid additional discovery and 1 confirmed LLM false positive
- deterministic → LLM → Human responsibility separation
- reproducible offline demo
- regression tests and GitHub Actions CI
- explicit limitations and public-safety checks

The core engineering principle is:

> **Use deterministic software for structural facts, AI for semantic review, and humans for final engineering judgment.**

## Building Next

I am extending the same engineering approach with a minimal AWS evidence path:

**Synthetic telemetry → AWS IoT Core → Lambda → S3 Evidence + CloudWatch**

The goal is not to demonstrate as many cloud services as possible. The goal is to show that an engineering workflow can be **deployed, observed, constrained, reproduced, and explained end-to-end**.

## What I Work On

### Systems Engineering & V&V
- Requirements engineering
- MBSE
- Requirement-to-test traceability
- HiL / ViL / MiL
- Test automation
- Failure analysis
- Evidence and approval workflows

### Automotive
- ADAS / automated-driving validation
- CANoe / CANalyzer
- MATLAB / Simulink / Stateflow
- System integration
- CI-based verification

### AI-assisted Engineering
- LLM review and evaluation
- deterministic guardrails
- human-in-the-loop engineering
- AI evaluation and failure analysis
- structured engineering evidence

### Cloud & DevOps
- AWS
- S3 / CloudWatch
- GitHub Actions
- Jenkins
- Git
- Python

## Current Direction

I am interested in engineering roles where **Automotive / SDV / Robotics / Physical AI** meet:

- Systems Architecture
- Verification & Validation
- AI-assisted engineering
- Engineering automation
- Cloud-connected development environments

My focus is not AI for its own sake, but using AI to improve how complex physical/software systems are **designed, verified, reviewed, and evidenced**.
