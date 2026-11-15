# Project Charter

> This charter records a feasible starting scope based on the supplied concept. Treat proposed details as provisional until the team and supervisor approve them.

## Project identity

- **Current project title recorded by the team:** Intelligent Learning and Growth Platform
- **Concept heading in the supplied brief:** AI-Powered Child Development Ecosystem
- **Concept subtitle:** An Intelligent Ecosystem for Learning, Personal Growth, and Child Development
- **Team:** Hossam Mohamed Abdelhakim Mohamed, Abdelrahman Ayman, Manar Abdelrahman Mohamed, Abrar Ahmed Hassan, Ahmed Mohamed Goda, Khaled Nabil Ali Mohamed, Zeinab Mohamed Ali Mohamed, and Melad Hani Boushra Ayad.
- **Supervisor:** [TODO]
- **Last updated:** [TODO]
- **Title decision:** Confirm the official title with the supervisor before submitting the cover page.

## Problem and motivation

**Problem hypothesis to validate:** Children differ in their current knowledge, interests, and pace of learning, while a single fixed sequence of lessons may not give each learner the support they need. The project will investigate whether a small personalized English-learning experience can make practice more relevant and help learners understand what to practice next. Support factual claims with sources in the final report.

## Proposed solution

Build a software-only, responsive web application, accessible through common phone, tablet, and desktop browsers. The first subsystem is a focused English Language Learning System for one age band selected with the supervisor. The proposed MVP combines a short level assessment, a limited set of learning activities, an AI tutor using an existing model/service, simple next-step recommendations, and progress tracking. A parent/guardian summary is a stretch feature if time and approval allow.

The broader child-development ecosystem, including academic learning across subjects, life skills, entertainment, a robot, and a Smart Mirror, is long-term vision and is not a promise to implement those features in this project.

## Goals and measurable objectives

| ID | Objective | Measure of success | Target / acceptance threshold |
| --- | --- | --- | --- |
| O1 | Deliver a usable software MVP for the approved initial English-learning scope. | Completion of approved functional requirements and end-to-end learner scenarios. | Define with supervisor in T01. |
| O2 | Provide relevant tutoring and next-step recommendations for the selected content. | Evaluation of answer quality, age-appropriateness, and recommendation relevance using an approved test set. | Define method and thresholds in T01/T08. |
| O3 | Protect child users and their data in the prototype. | Review of privacy/safety requirements and passing relevant test cases. | Define with supervisor before any real-user evaluation. |

## Scope

### In scope for the proposed MVP

- One responsive web application; no special hardware is required.
- One initial learner age band or school stage, to be selected before implementation.
- English as the initial learning language; Arabic explanations may be included if approved.
- A minimal learner profile, starting-level assessment, and a small set of selected English-learning activities.
- An AI tutor based on an existing model/service and a simple, explainable recommendation approach.
- Basic progress tracking and a limited evaluation of the implemented features.
- Child-appropriate interaction, data minimization, and privacy/safety controls.

### Out of scope for the proposed MVP

- Physical hardware, robot, Smart Mirror, sensors, or firmware.
- Full curriculum coverage or complete implementation of all four development pillars.
- Separate native applications for every platform.
- Fine-tuning or training a large language model from scratch.
- A full 24/7 AI companion or comprehensive parent dashboard.
- Collection of identifiable child data without documented approvals and consent.

See `project-overview.md` for the full vision, proposed boundaries, and decisions to confirm.

## Stakeholders and users

| Stakeholder / user | Need or interest | How the project affects them |
| --- | --- | --- |
| Child learner in the approved age band | Safe, understandable, engaging English-learning support. | Uses lessons, assessment, tutor, recommendations, and progress view. |
| Parent or guardian | Appropriate oversight and confidence in how data is handled. | May receive a limited progress summary if that feature is approved. |
| Content administrator / educator | Manage or review the selected learning content. | May maintain the small content set used in the MVP. |
| Supervisor / institute | Feasible, ethical, and demonstrable graduation project. | Approves scope, evaluation method, and required report format. |

## Constraints and assumptions

- **Hardware:** None is planned or required for the current project.
- **Platform:** The MVP should be one responsive web application; the exact stack is not selected yet.
- **Scope:** The full ecosystem is too broad for one MVP; the first implementation focuses on the language-learning subsystem.
- **Target users:** The brief mentions ages 6–18, but the MVP must select one manageable age band.
- **AI:** Use an existing model/service unless a more ambitious model approach is approved and supported by data and time.
- **Data and privacy:** Use synthetic, public, or properly approved and de-identified data for development and evaluation.
- **Safety:** The system is educational support, not a replacement for parents, teachers, or qualified professionals.
- **Time, budget, and resource constraints:** [TODO]

## High-level milestones

| Milestone | Evidence / deliverable | Target date | Owner |
| --- | --- | --- | --- |
| Scope approval | Approved MVP, target age band, feature list, and evaluation plan. | [TODO] | Hossam Mohamed Abdelhakim Mohamed |
| Requirements and design | Reviewed requirements, use cases, UX flows, diagrams, and software architecture. | [TODO] | Task owners in `TASK_ASSIGNMENTS.md` |
| MVP implementation | Working responsive application and selected AI tutor/personalization features. | [TODO] | Task owners in `TASK_ASSIGNMENTS.md` |
| Evaluation and report | Test evidence, reviewed report chapters, and final presentation. | [TODO] | Task owners in `TASK_ASSIGNMENTS.md` |

## Approval and open questions

- **Supervisor-approved decisions:** [TODO]
- **Open questions:** Confirm official title, target age band, exact language activities, Arabic support, parent-summary scope, allowed LLM/model, data/consent rules, and evaluation method.
