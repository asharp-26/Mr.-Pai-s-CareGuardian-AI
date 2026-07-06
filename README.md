# Mr Pai's CareGuardian AI

## Overview

Mr Pai's CareGuardian AI is a multi-agent elderly care assistant developed using Google's Antigravity Platform and Agent Development Kit (ADK).

The system helps elderly individuals manage medication schedules, medication adherence, emergency situations, and healthcare-related interactions through intelligent intent classification and specialized AI agents.

CareGuardian AI was inspired by real-world elderly care challenges, including medication management, adherence tracking, and emergency awareness for senior citizens.

---

## Problem Statement

Elderly individuals frequently face challenges such as:

- Forgetting medication schedules
- Missing prescribed doses
- Difficulty tracking medication adherence
- Delayed response during emergency situations
- Lack of caregiver visibility into daily medication routines

CareGuardian AI addresses these challenges through a multi-agent architecture that provides scheduling, compliance monitoring, emergency guidance, and healthcare-focused assistance.

---

## Solution Overview

CareGuardian AI uses an intelligent classifier-driven workflow to route user requests to specialized agents.

The system supports:

- Medication Scheduling
- Medication Compliance Tracking
- Emergency Detection and Guidance
- Healthcare-Focused Query Handling
- Multi-Agent Workflow Orchestration

---

## System Architecture

### Core Components

### Classifier Agent

Responsible for:

- Intent Detection
- Request Classification
- Agent Routing
- Context-Based Decision Making

### Schedule Agent

Responsible for:

- Creating medication schedules
- Updating medication schedules
- Managing recurring reminders
- Schedule confirmation

### Compliance Agent

Responsible for:

- Recording medication adherence
- Tracking medication acknowledgements
- Monitoring compliance status
- Maintaining adherence history

### Emergency Agent

Responsible for:

- Emergency symptom identification
- Emergency classification
- Safety guidance
- Escalation recommendations

### Shared Session Memory

Responsible for:

- Context preservation
- State management
- Cross-agent communication
- Session continuity

### Workflow Manager

Responsible for:

- Workflow orchestration
- Agent coordination
- State transitions
- Response management

---

## Key Features

### Medication Scheduling

Example:

Input:

Schedule my BP tablet at 8 AM daily

Output:

Medication schedule created successfully.

---

### Medication Compliance Tracking

Example:

Input:

I took my medicine

Output:

Medication adherence recorded successfully.

---

### Emergency Detection

Example:

Input:

I have chest pain and difficulty breathing

Output:

Emergency guidance and escalation recommendations provided.

---

### Unrelated Query Handling

Example:

Input:

Tell me a joke

Output:

Healthcare-focused response generated.

---

## Example Workflow

User Request

↓

Classifier Agent

↓

Intent Classification

↓

Appropriate Agent Selection

↓

Agent Execution

↓

Response Generation

↓

User Notification

---

## Validation Summary

The system was validated using dedicated validation scenarios for:

- Schedule Agent
- Reminder Agent
- Compliance Agent
- Emergency Agent
- Classifier Agent
- Workflow Execution
- End-to-End System Testing

### Validation Results

| Validation Area | Status |
|-----------------|---------|
| Schedule Agent | PASS |
| Reminder Agent | PASS |
| Compliance Agent | PASS |
| Emergency Agent | PASS |
| Classifier Agent | PASS |
| Workflow Validation | PASS |
| End-to-End Validation | PASS |

---

## Test Results

### Unit Tests

PASS

### Integration Tests

PASS

### End-to-End Tests

PASS

### Overall Status

All validation scenarios completed successfully.

---

## Technology Stack

- Google Antigravity Platform
- Google Agent Development Kit (ADK)
- Google Gemini
- Python
- Google Cloud
- Multi-Agent Architecture
- Session Memory Management

---

## Screenshots

The project includes demonstration screenshots covering:

1. Medication Scheduling
2. Medication Compliance Tracking
3. Emergency Detection
4. Unrelated Query Handling

---

## Future Enhancements

Planned future enhancements include:

- Smartwatch Integration
- Voice-Based Medication Assistance
- SMS Notification Support
- Caregiver Dashboard
- Hospital Integration
- Medication Analytics
- Health Monitoring Integration

---

## Project Structure

```text
CareGuardian_AI/

├── app/
│   ├── agent.py
│   └── fast_api_app.py
│
├── tests/
│   ├── unit/
│   └── integration/
│
├── screenshots/
│
├── documentation/
│
├── README.md
│
└── Demo.mp4
```

---

## Deployment Platform

Google Antigravity Platform

Google Agent Development Kit (ADK)

Gemini Enterprise AI

---

## Author

### Asha R Pai

Capstone Project Submission

Google Antigravity AI Program

July 2026

---

## Acknowledgements

Special thanks to Google Antigravity, Google ADK, and the Gemini AI ecosystem for enabling rapid development of multi-agent AI applications for real-world healthcare scenarios.

---

## Conclusion

CareGuardian AI demonstrates how agentic AI can support elderly care through intelligent medication scheduling, adherence tracking, emergency awareness, and healthcare-focused assistance.

The system provides a scalable foundation for future caregiver support, remote health monitoring, and digital healthcare solutions.