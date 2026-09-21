# InspectReady — Business Analysis & Product Validation

**Know before the inspector arrives.**

InspectReady is a contractor-focused **pre-inspection readiness concept** developed during *Risk & Return: Turning Data Into Business Decisions*, a Build Project in **The Build Fellowship by Open Avenues Foundation**.

![InspectReady prototype](prototype/inspectready-prototype.svg)

## Executive Summary

Contractors can finish a phase of work and still discover code-related or documentation issues only when the municipal inspector arrives. The result can be rework, repeat visits, idle labor, rescheduling, and downstream project delays.

This project asks a business question before assuming the product should be built:

> **Can a pre-inspection readiness workflow reduce the cost and uncertainty contractors experience before municipal inspections?**

The work covers problem framing, qualitative research, competitor analysis, TAM/SAM/SOM modeling, risk analysis, ideation, prototyping, and a final business recommendation.

## My Role

**Student Consultant — The Build Fellowship, Open Avenues Foundation**

I worked across the full early-stage analysis cycle:

- problem discovery and framing
- primary-user definition
- qualitative customer research
- competitor and alternative-solution research
- TAM / SAM / SOM market sizing
- risk and assumption analysis
- Crazy 8's ideation
- solution sketching
- prototype development
- business-model hypotheses
- final recommendation and presentation

## Problem

General contractors may complete work without a reliable way to determine whether the job is truly ready for an official municipal inspection.

If the inspection identifies an issue, the contractor may need to:

- correct completed work
- bring crews back to the jobsite
- schedule another inspection
- delay dependent work
- absorb additional labor and schedule cost

The core user question is:

> **Is my job actually ready for inspection?**

## Proposed Solution

InspectReady introduces a structured pre-inspection workflow.

1. Select the project and inspection type.
2. Capture evidence with a phone camera or optional drone scan.
3. Review possible issues and missing evidence.
4. Correct identified problems before the official inspection.
5. Escalate uncertain cases to a human/private inspector when appropriate.
6. Produce an inspection-readiness report.

The concept is an **inspection-readiness assistant**. It does not replace municipal authority and does not guarantee inspection approval.

## Research & Validation

The qualitative research examined contractor and forum discussions for recurring pain points.

Directional findings summarized in the project deck included:

- **62%** — failed inspections, rework, or repeat inspection visits
- **54%** — slow or unpredictable inspection timelines
- **46%** — code-interpretation or inspector-expectation challenges

These percentages come from a **qualitative sample** and should not be interpreted as national survey statistics.

![Market validation](research/market-validation.svg)

## Market Model

A bottom-up TAM / SAM / SOM model was used to test whether the opportunity could support a viable business.

| Market | Modeled opportunity |
|---|---:|
| TAM | ~**$12B** annually |
| SAM | ~**$255M** |
| SOM | ~**$2.5M** |

The SAM model used approximately **212K U.S. residential contractor establishments** and assumed annual pricing. The SOM used approximately **2,100 early customers** and assumed pricing.

These are modeled estimates, not audited market figures. Pricing and reachable-customer assumptions require primary validation.

## Competitive Landscape

The research reviewed several categories of alternatives:

- **Municipal systems:** Accela, OpenGov
- **Construction management:** Procore, Autodesk Construction Cloud
- **Inspection/checklist software:** SafetyCulture
- **Emerging AI inspection tools:** Specta, Infrava Inspect, Tradei Vision
- **Human/private inspection services**

The opportunity explored is a contractor-facing workflow combining **field evidence capture, readiness analysis, optional drone capture, human escalation, and a final readiness report**.

## Business-Model Hypotheses

The project considered:

- SaaS subscription
- pay-per-pre-inspection
- private-inspector marketplace commission
- premium drone-inspection add-on

These remain hypotheses until willingness-to-pay testing is completed.

## Recommendation

The current recommendation is **not to build the full product yet**.

The next decision should be based on stronger primary evidence around:

- frequency and cost of failed inspections
- contractor willingness to pay
- trust in AI-assisted findings
- the best inspection category for an MVP
- jurisdiction-specific code-data availability

## Next Validation Steps

1. Interview 10–15 general contractors.
2. Interview building and private inspectors.
3. Measure failure frequency and rework cost.
4. Test willingness to pay.
5. Test contractor trust in AI-assisted findings.
6. Choose one inspection category for the MVP.
7. Research jurisdiction-specific code-data access.
8. Run a small real-world contractor pilot.

## Project Deliverables

- **docs/case-study.md** — concise case study and recommendation
- **docs/project-process.md** — end-to-end analysis process
- **research/problem-validation.md** — problem research
- **research/competitive-landscape.md** — competitor review
- **research/market-sizing.md** — TAM / SAM / SOM model
- **prototype/** — prototype assets
- **ideation/** — Crazy 8's and solution sketches
- **presentation/final-pitch-deck.md** — final pitch

## Repository Structure

- **docs/** — case study, metadata, and project process
- **research/** — validation, competitors, and market sizing
- **ideation/** — Crazy 8's and solution sketches
- **prototype/** — product concept assets
- **presentation/** — final pitch materials

## Program Context

**Program:** The Build Fellowship by Open Avenues Foundation  
**Build Project:** *Risk & Return: Turning Data Into Business Decisions*  
**Project:** InspectReady

---

This repository documents an early-stage business-analysis and prototype project. It is not a production inspection system and should not be used as a substitute for licensed professional or municipal inspection.
