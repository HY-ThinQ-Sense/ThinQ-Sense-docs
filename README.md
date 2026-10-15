# ThinQ Sense — Software Engineering Documentation

> CSE406 — Software Engineering | Hanyang University, Fall 2026

This repository is the source of truth for CSE406 academic deliverables. It also hosts shared design documents for the integrated ThinQ Sense project.

## Official Milestones

| Milestone | Expected artifact | Due date in provided notice |
| --- | --- | --- |
| A. Requirement Analysis | IEEE-format proposal / requirements paper | Oct. 23 (first), Oct. 30 (second) |
| B. Specification | Structured system analysis | To be announced |
| C. Design | Architecture design | To be announced |
| D. Implementation & Integration | Source code, testing, use cases | To be announced |
| E. Demo / Final | Presentation, user guide, installation guide, final paper / code | To be announced |

**First submission:** LMS, one per group by Oct. 23 at 13:00. Print copies for Oct. 23 and Oct. 30 classes. Register group and tentative topic on the CSE406 spreadsheet.

## Suggested Structure

```text
A-requirements/    # IEEE source, exported PDFs, stakeholder roles, requirements
B-specification/   # use cases, models, interfaces, constraints
C-design/          # architecture, sequences, data model, security design
D-verification/    # test plan, evaluation, traceability matrix
E-final/           # presentation, guide, installation and final documents
assets/            # diagrams and figures with permissions
```

## Core Requirements to Refine

- Sensor inputs shall be transformed into schema-validated semantic events.
- The world model shall maintain room occupancy and user activity with timestamps.
- The planner shall explain each appliance action with applicable constraints.
- A simulation adapter shall feed the same interfaces as real sensors.
- The prototype shall not expose raw video/audio in the central context API.

Draft requirements only; formal priority, measurable acceptance criteria, and stakeholder approval are pending.

## Team Roles (for the report)

- User: TBD
- Customer: TBD
- Software developer: TBD
- Development manager: TBD
