# LG-EYEAR-docs — CSE406 Software Engineering Deliverables

**Hanyang University · Fall 2026 · CSE406 Software Engineering**

**Project:** EYEAR: Eyes and Ears for Proactive Smart Home Orchestration through Spatial Awareness and Multi-Agent Collaboration

This is the source of truth for IEEE-formatted coursework documents and their LaTeX source. The submitted Proposal/Requirements document is preserved as **Submission A v1**; later updates should be explicitly versioned rather than silently overwriting the submitted artifact.

## Official Milestones (updated Phase 2 notice)

| Stage | Required deliverable | Tentative due dates |
| --- | --- | --- |
| A — Requirement Analysis | IEEE-format Proposal/Requirement document | **Oct. 23 / Oct. 30, 2026** |
| B — Specification | Specification document with structured system analysis | **Nov. 6 / Nov. 13, 2026** |
| C — Design | Architecture design document | **TBA** |
| D — Implementation & Integration | Source code, testing, use cases | **TBA; C and D submitted together per notice** |
| E — Demo / Final | Presentation, user guide, installation guide, final paper/source code | **TBA** |

**Submission procedure:** one LMS submission per group and a printed copy in class. The course notice disallows late submission. Confirm exact submission time and any revised LMS instructions for each deadline. The dates above come from the updated *Phase 2 — Term Project II* handout; its dates are expressly **tentative**.

## Submission A — Completed (Oct. 23, 2026)

Submitted as `SE_G05_EYEAR.pdf` (4 pages). It contains:

- Title, four authors and group `EYEAR`
- Abstract and index terms
- Team responsibilities
- Introduction: motivation, user needs, related software context, system boundary
- Requirements **R-01 to R-26**
- LG ThinQ ON concept and ESPHome LD2450 references

Preserve the *exact submitted PDF* and matching `.tex` source in `A-requirements/submitted-2026-10-23/`. Do not confuse planned corrections with already submitted content. The Oct. 30 second deadline is part of the A milestone; its revision expectations should be confirmed through the LMS/instructor.

## Submission B — Next Priority (Nov. 6 / Nov. 13)

The updated notice requires **all** of the following:

1. Update group metadata, including repository URL and topic, in the official spreadsheet.
2. Set up a version-control system; GitHub public repositories are recommended.
3. Upload the **LaTeX source for both A and B** to version control (not just PDFs).
4. Add **Section III — Development environment**:
   - **A. Choice of software development platform:** OS/platform, programming languages, reasons for selection, detailed environment versions and machine resources, **cost estimate** including hardware and software purchases. Commercial cloud is optional bonus, not mandatory.
   - **B. Software in use:** identify existing software, frameworks and algorithms and provide appropriate references.
   - **C. Task distribution:** who is responsible for which tasks; explicitly allowed to defer to the design phase.
5. Add **Section IV — Specifications**: explain **how every relevant requirement R-01–R-26 can be achieved**, at least to pseudocode/algorithm level; diagrams are recommended.
6. Revise Introduction or Requirements if necessary and keep the Specifications consistent with the revised requirement IDs and scope.

## Suggested Document Structure

```text
A-requirements/
  submitted-2026-10-23/
    SE_G05_EYEAR.pdf
    main.tex                   # exact corresponding source
  revised-2026-10-30/          # if applicable
B-specification/
  source/main.tex              # IEEE document including sections I–IV
  figures/
  submitted-2026-11-06/
  revised-2026-11-13/
C-design/
D-verification/
E-final/
assets/
```

## B Specification Work Breakdown

| Workstream | Expected specification details |
| --- | --- |
| Local EYEAR Node | Video/audio/mmWave input adapters, local model/pipeline outputs, missing-input behavior |
| Semantic Events | JSON schema, field constraints, sample messages, timestamps and validation |
| Context Engine | Multi-room aggregation, world-state representation, freshness/confidence rules |
| Agents | Cleaning and quiet/activity proposals, responsibilities, decision interfaces |
| Orchestrator | Optional LLM supervision, deterministic plan validation, priorities, replanning |
| Demo | Replay clock, virtual action API, 3D synchronization and execution feedback |
| Nonfunctional | Latency measurement, security/privacy boundary, resilience, acceptance tests |

For R-01–R-26, maintain a **requirements traceability matrix** with requirement ID, implementing component, interface, procedure/pseudocode, and test case. State explicitly which advanced features are optional or conceptual.

## Source of Truth and Links

- [Main system](https://github.com/HY-LG-EYEAR/LG-EYEAR)
- [Perception/AI](https://github.com/HY-LG-EYEAR/LG-EYEAR-ai)
- [ITE351 blog](https://github.com/HY-LG-EYEAR/LG-EYEAR-blog)
- [CSE406 group/topic registration spreadsheet](https://docs.google.com/spreadsheets/d/1dzb9zCfWbEPEt4Nv0I6fo3k4W3tYgr1VL0zd_ijWwxI/edit?usp=sharing)
