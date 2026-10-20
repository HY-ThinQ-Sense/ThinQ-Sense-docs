# ThinQ Sense — Software Engineering Documentation

**CSE406 — Software Engineering**  
**26-2 Hanyang University**

### Project Title

**ThinQ Sense: A Spatially Aware Multi-Agent System for Predictive and Proactive Smart Home Orchestration**

## Overview

This repository contains the software engineering documentation and academic deliverables for the ThinQ Sense project.

The project proposes a spatially aware multi-agent system that interprets household activities, predicts future conditions, and dynamically coordinates home appliance operations.

The software engineering work focuses on requirements analysis, system modeling, modular architecture, agent integration, constraint-based planning, testing, and verification.

## Project Scope

The proposed system consists of five main layers:

1. **Perception Layer:** Processes multimodal sensing inputs into semantic events.
2. **Context Layer:** Maintains a continuously updated household world model.
3. **Prediction Layer:** Estimates future activities and spatial states.
4. **Decision Layer:** Coordinates specialized agents through global planning and policy validation.
5. **Simulation Layer:** Evaluates system behavior through an interactive 3D smart home digital twin.

The initial academic prototype does not require physical LG appliance control.

## Official Deliverables

| Milestone | Deliverable | Due Date |
|---|---|---|
| A. Requirements Analysis | IEEE-format Proposal / Requirements Document | Oct. 23 and Oct. 30, 2026 |
| B. Specification | Structured System Analysis | To be announced |
| C. Design | Architecture Design Document | To be announced |
| D. Implementation & Integration | Source Code, Testing, Use Cases | To be announced |
| E. Demo / Final | Presentation, User Guide, Installation Guide, Final Paper / Code | To be announced |

**First submission:** October 23, 2026, 13:00, through LMS. Printed copies are required in class on October 23 and October 30.

## Documentation Structure

```text
A-requirements/
  proposal/
  stakeholder-analysis/
  functional-requirements/
  non-functional-requirements/
  use-cases/

B-specification/
  use-case-diagrams/
  state-models/
  domain-models/
  interface-contracts/

C-design/
  system-architecture/
  perception-design/
  world-model-design/
  multi-agent-design/
  optimization-design/
  security-design/
  digital-twin-design/

D-verification/
  test-plans/
  test-cases/
  integration-tests/
  scenario-tests/
  traceability-matrix/

E-final/
  presentation/
  user-guide/
  installation-guide/
  final-paper/
```

## Core Functional Requirements

The system should support:

- Sensor event ingestion and semantic normalization
- Real-time occupant and room state management
- Household state prediction
- Specialized agent proposal generation
- Multi-agent conflict resolution
- Constraint-based action planning
- Dynamic replanning after state changes
- Appliance action intent generation
- Simulated execution through a 3D digital twin
- Decision logging and explanation
- Live sensing and virtual scenario inputs

## Non-Functional Requirements

The system should address:

- Privacy and local sensor processing
- Modular architecture and maintainability
- Extensibility of sensors and appliance agents
- Real-time responsiveness
- Reliability under sensor failure
- Security and access control
- Testability and reproducibility
- Clear separation of proposed and implemented functions

## Major Use Cases

### UC-01 — Adaptive Robot Cleaning

The robot cleaning plan is dynamically adjusted based on real-time occupancy, predicted room availability, and household constraints.

### UC-02 — Predictive Sleep Preparation

The system anticipates bedtime-related activities and coordinates room conditions before explicit commands.

### UC-03 — Context-Aware Quiet Home

The orchestrator coordinates appliance activities to reduce disturbances during sleep, meetings, and rest.

### UC-04 — Personalized Comfort

The system balances occupant preferences, spatial context, and operational constraints when planning climate-related actions.

### UC-05 — Privacy-Aware Presence Sensing

The system supports reduced sensing capabilities when visual data collection is disabled.

## Verification Strategy

The project will evaluate the system through:

- Unit testing
- API contract testing
- Integration testing
- Scenario-based functional testing
- Constraint violation testing
- Replanning behavior verification
- Performance and latency measurements

Every major requirement should be mapped to one or more verification cases.

## Related Repositories

- [Main System](https://github.com/HY-ThinQ-Sense/ThinQ-Sense)
- [AI Research](https://github.com/HY-ThinQ-Sense/ThinQ-Sense-ai)
- [Technical Blog](https://github.com/HY-ThinQ-Sense/ThinQ-Sense-blog)

## Status

Requirements analysis and architecture planning are in progress.

Subsequent milestone dates will be updated according to official course announcements.
