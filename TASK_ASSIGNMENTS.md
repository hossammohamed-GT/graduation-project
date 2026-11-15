# Task Assignments

## Working Project Direction

**Project title:** Intelligent Learning and Growth Platform

The task breakdown below assumes a proposed web platform that helps learners choose a learning goal, assess their current level, follow a personalized learning path, and track progress. A learner and an instructor/administrator are proposed user roles. **Confirm the target users, first learning domain, and feature scope with the supervisor before treating this direction as final.**

## How to Use This File

- Assign one primary owner to each task and add contributors if needed.
- Check off each relevant deliverable as it is completed and reviewed.
- If an optional hardware or firmware task is out of scope, set its status to **N/A** and record the supervisor-approved reason.
- Mark a task **Complete** only after its deliverables are saved in the listed location and reviewed by the team.

**Status values:** Not started · In progress · In review · Complete · N/A

---

## T01 — Project Scope and Success Criteria

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `docs/planning/`

### Deliverables

- [ ] Describe the problem the platform will solve and who experiences it.
- [ ] Choose and justify the initial learner group and one manageable learning domain for the first version.
- [ ] List the project goals and measurable success criteria.
- [ ] Define what is in scope and out of scope for the first version.
- [ ] Identify stakeholders, assumptions, constraints, risks, and dependencies.
- [ ] Review and record supervisor approval in `docs/planning/project-charter.md`.

## T02 — Background Research and Related Work

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `docs/research/`, `docs/final-report/references/`

### Deliverables

- [ ] Record the research question, search terms, and source-selection criteria.
- [ ] Find reliable sources about personalized learning, learning platforms, and recommendation methods relevant to the approved scope.
- [ ] Compare relevant existing platforms or projects: target users, main features, personalization approach, and limitations.
- [ ] Identify the gap or specific need the proposed project addresses.
- [ ] Summarize the findings in `docs/research/literature-review.md` and provide complete, traceable citations.

## T03 — Requirements and Use Cases

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `docs/requirements/`

### Deliverables

- [ ] **Functional requirements:** Write testable, uniquely identified requirements (FR-001, FR-002, ...) for the in-scope features. Consider account/profile setup, choosing a learning goal, a starting-level assessment, browsing learning content, receiving recommendations, completing learning activities or quizzes, viewing progress, and instructor/administrator content management. Include only features approved for the first version.
- [ ] **Non-functional requirements:** Define measurable expectations for usability, accessibility, privacy, security, performance, reliability, and compatibility where relevant.
- [ ] **User roles and actors:** Define the learner and any instructor/administrator roles, including their goals and permissions.
- [ ] **Use cases:** Document each in-scope user goal with its actor, preconditions, trigger, main steps, alternative/error steps, postconditions, and related requirement IDs.
- [ ] **Priorities and acceptance criteria:** Mark requirements by priority and state how each important requirement will be verified.
- [ ] **Traceability:** Link project objectives to requirements and planned tests in `docs/requirements/requirements.md` and `docs/requirements/use-cases.md`.
- [ ] Review the requirements with the team and supervisor; record unresolved questions instead of guessing.

## T04 — System Analysis and Analysis Diagrams

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `docs/system-design/diagrams/`

### Deliverables

- [ ] Create a system-context diagram showing the platform boundary, users, and external services or systems.
- [ ] Create a functional decomposition or feature diagram for the approved platform scope.
- [ ] Create a workflow or flowchart for the learner journey from goal selection through progress review.
- [ ] Create data-flow diagrams for important activities, such as assessment and recommendation, with deeper process detail where useful.
- [ ] Create a use-case diagram that matches the written use cases and approved actors.
- [ ] Create sequence diagrams for the most important scenarios, such as taking an assessment and receiving a recommendation.
- [ ] Add a short explanation, caption, and source note for each diagram; keep terminology consistent with the requirements.
- [ ] Save editable diagram sources in `docs/system-design/diagrams/` and report-ready exports in `assets/diagrams/`.

## T05 — System Architecture and Detailed Design

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `docs/system-design/`

### Deliverables

- [ ] Draw and explain the high-level architecture and the responsibility of each component.
- [ ] Describe the proposed application, server/API, database, and recommendation component only if each is in the approved design.
- [ ] Design the main data entities and their relationships, such as users, goals, learning content, assessments, attempts, recommendations, and progress, as applicable.
- [ ] Document key interfaces, API operations, data flow, and integration points.
- [ ] Prepare basic user-interface wireframes for the agreed learner and administrator workflows.
- [ ] Record technology and design decisions with alternatives considered and reasons for the selected approach.
- [ ] Address relevant privacy, security, accessibility, and safety considerations and link design elements to requirement IDs.

## T06 — Hardware and Electronics Design (Optional)

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `hardware/`

### Deliverables

- [ ] First confirm whether the approved project requires a physical device or electronics.
- [ ] If it is a software-only learning platform, mark this task **N/A** and record the approved reason; do not invent hardware work.
- [ ] If hardware is approved, document the component choices, purpose, compatibility, cost, and bill of materials.
- [ ] Provide the required physical design, circuit/wiring diagrams, interface details, and safety notes.
- [ ] Keep editable design files and clear prototype evidence in the appropriate `hardware/` subfolders.

## T07 — Data Collection and Data Management

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `data/`, `docs/implementation/`

### Deliverables

- [ ] Identify the data needed for learning content, assessments, and recommendations; distinguish content data from learner activity data.
- [ ] Record each data source, owner, license/permission, version, and collection method.
- [ ] Define the data schema, labels, validation rules, and any preparation or preprocessing steps.
- [ ] Use synthetic, public, or explicitly approved and de-identified learner data; document privacy, consent, retention, and access controls.
- [ ] If model training is in scope, document a reproducible train/validation/test split and prevent data leakage.
- [ ] Store only permitted, appropriately sized data in Git; keep large or restricted datasets in approved external storage and document the reference.

## T08 — AI/ML Development and Evaluation (If Applicable)

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `src/ml/`, `docs/implementation/`

### Deliverables

- [ ] Define precisely what the intelligent feature recommends, what inputs it uses, and what output the learner sees.
- [ ] Implement a simple, explainable baseline first, such as recommendations based on the learner's goal, assessment result, and progress.
- [ ] Use a machine-learning model only if suitable, permitted data and a measurable benefit are available; document the model and its limitations.
- [ ] Evaluate recommendations with appropriate metrics and a clear test procedure; compare against the baseline where possible.
- [ ] Document reproducibility details, assumptions, failure cases, and safeguards against misleading or unsuitable recommendations.
- [ ] Integrate the approved recommendation feature with the application and add tests for its inputs and outputs.

## T09 — Application and Software Implementation

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `src/application/`, `src/shared/`

### Deliverables

- [ ] Set up the application structure and document verified build/run instructions.
- [ ] Implement the approved learner registration/profile and learning-goal workflow.
- [ ] Implement the agreed learning-content catalog or learning-path pages.
- [ ] Implement the starting-level assessment and learning activities or quizzes included in scope.
- [ ] Display personalized recommendations from the approved rule-based or AI/ML component.
- [ ] Provide a progress view showing completed activities and the learner's next step.
- [ ] Implement instructor/administrator content-management features if they are in scope.
- [ ] Add appropriate validation, error handling, access control, and user feedback.
- [ ] Keep application behavior aligned with the approved requirements and add or update automated tests.

## T10 — Firmware and Prototype Integration (Optional)

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `src/firmware/`, `hardware/`

### Deliverables

- [ ] First confirm whether the approved project includes programmable hardware.
- [ ] If it is a software-only learning platform, mark this task **N/A** and record the approved reason.
- [ ] If applicable, implement and document the required firmware and communication interfaces.
- [ ] Integrate the physical prototype with the application and verify the end-to-end behavior.
- [ ] Record setup, flashing, integration, safety, and troubleshooting instructions, plus test evidence.

## T11 — Testing and Validation

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `tests/`, `docs/testing/`

### Deliverables

- [ ] Create a test plan linked to requirement IDs and acceptance criteria.
- [ ] Add unit tests for important application logic and recommendation behavior.
- [ ] Add integration tests for the application, API, database, and recommendation component where applicable.
- [ ] Test end-to-end learner scenarios: goal selection, assessment, recommended path, activity completion, and progress update.
- [ ] Check usability and accessibility with an approved, ethical test approach; do not collect unnecessary personal information.
- [ ] Record environment, steps, expected and actual results, pass/fail status, defects, retests, and evidence.
- [ ] Summarize which objectives were met and which limitations remain.

## T12 — Final Report: Introduction and Related Work

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `docs/final-report/chapters/`

### Deliverables

- [ ] Complete Chapter 1: project context, problem, scope and constraints, impact, methodology, objectives, definitions, and project overview.
- [ ] Explain the specific problem and target learners; do not make unsupported claims.
- [ ] Complete Chapter 2: background, relevant history or concepts, related platforms/projects, comparison, and project gap.
- [ ] Add citations for factual claims and keep terminology consistent with the approved charter.
- [ ] Save drafts in the Chapter 1 and Chapter 2 files and request team/supervisor review.

## T13 — Final Report: System Analysis and Design

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `docs/final-report/chapters/`

### Deliverables

- [ ] Complete Chapter 3 with system requirements, actors, workflows, and relevant analysis diagrams.
- [ ] Complete Chapter 4 with architecture, component design, data model, interfaces, and relevant wireframes or design illustrations.
- [ ] Ensure every diagram is readable, explained in the text, captioned, and consistent with the latest system design.
- [ ] Cross-reference requirements and design decisions where useful; cite external sources.
- [ ] Save drafts in the Chapter 3 and Chapter 4 files and request team/supervisor review.

## T14 — Final Report: Implementation, Conclusion, and Appendices

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `docs/final-report/chapters/`, `docs/final-report/appendices/`

### Deliverables

- [ ] Complete Chapter 5 with the verified software stack, implemented features, integration, and clear screenshots or prototype evidence.
- [ ] Report test/evaluation results accurately and link them to the objectives and test records.
- [ ] Complete Chapter 6 with the conclusion, achieved objectives, limitations, and realistic future work.
- [ ] Add only relevant appendices, such as setup instructions, selected code listings, or additional test material.
- [ ] Remove secrets, private data, unsupported claims, and unused template placeholders before review.

## T15 — References, Figures, and Final Report Quality Review

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `docs/final-report/`, `assets/`

### Deliverables

- [ ] Ensure every in-text citation has a matching reference and every listed source is used in the report.
- [ ] Apply the citation style, report language, page layout, and formatting required by the institute.
- [ ] Generate the final table of contents and list of figures from the finished document; update all page numbers.
- [ ] Check chapter/section/figure numbering, captions, image readability, spelling, grammar, and consistent terminology.
- [ ] Search for and resolve every `[TODO]`, sample name, old example, broken link, and unapproved claim.
- [ ] Obtain a final team and supervisor review and prepare the required submission format.

## T16 — Presentation and Project Demonstration

- **Assigned to:** ____________________
- **Status:** Not started
- **Main location:** `docs/presentation/`, `assets/`

### Deliverables

- [ ] Prepare slides covering the problem, target learners, goals, solution, architecture, key features, and evaluation results.
- [ ] Write a timed demonstration plan for the learner workflow and the intelligent recommendation feature.
- [ ] Use a verified demo account and safe, non-sensitive sample data.
- [ ] Prepare backup screenshots or a recording in case the live demonstration fails.
- [ ] Divide speaking roles and rehearse the complete presentation and demonstration.
- [ ] Ensure the presentation's claims match the implemented system and final report.
