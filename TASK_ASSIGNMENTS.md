# Task Assignments

## Project Direction and MVP Boundary

- **Current project title recorded by the team:** Intelligent Learning and Growth Platform.
- **Broader concept heading in the supplied brief:** AI-Powered Child Development Ecosystem.
- **Concept subtitle:** An Intelligent Ecosystem for Learning, Personal Growth, and Child Development.
- **Title decision:** Keep the current title for now; confirm the official title and subtitle with the supervisor before finalizing the cover page.

The supplied brief describes a much larger child-development ecosystem. The proposed graduation-project MVP is **software-only** and starts with one responsive web application for the **English Language Learning System**, for one age band chosen with the supervisor. It should work in common mobile, tablet, and desktop browsers; do not build separate native apps for every device in the MVP.

### Proposed MVP features

- [ ] Choose one initial age band and a small set of English-learning activities.
- [ ] Provide a minimal learner profile and starting-level assessment.
- [ ] Deliver selected vocabulary/grammar or other approved language activities.
- [ ] Provide an age-appropriate AI tutor using an existing model/service.
- [ ] Suggest a simple next activity or short learning plan using assessment and progress.
- [ ] Track completed activities and basic learning progress.
- [ ] Include a basic parent/guardian progress summary only if approved and time allows.

**Not implementation commitments for this project:** hardware, a robot, a Smart Mirror, firmware, camera/voice interfaces, full academic curriculum, all four development pillars, all ages 6–18, separate native apps, a 24/7 companion, a full parent dashboard, and training/fine-tuning a large language model. These may be discussed as long-term vision or future work only.

## How to Use This File

- These owner assignments are provisional and can be changed by the team at any time.
- The supplied roster gives specific expertise for Hossam (team leadership/full-stack development) and Melad (AI/ML); assignments for other members are a balanced starting point, not assumptions about their skills.
- Check off each relevant deliverable as it is completed and reviewed.
- Keep statuses current: **Not started**, **In progress**, **In review**, **Complete**, or **N/A**.
- Mark a task **Complete** only after its deliverables are saved in the listed location and reviewed by the team.

---

## T01 — Project Scope and MVP Success Criteria

- **Assigned to:** Hossam Mohamed Abdelhakim Mohamed (Eng. Hossam)
- **Status:** Not started
- **Main location:** `docs/planning/`

### Deliverables

- [ ] Confirm the official project title/subtitle and the exact project problem with the supervisor.
- [ ] Select one target age band or school stage for the first version; do not scope all ages 6–18 at once.
- [ ] Confirm that the English Language Learning System is the first subsystem to deliver.
- [ ] Select a small, achievable set of learning activities and separate MVP features from stretch goals and future vision.
- [ ] Define measurable project objectives, success criteria, constraints, assumptions, and risks.
- [ ] Record the approved decisions in `docs/planning/project-charter.md` and `docs/planning/project-overview.md`.

## T02 — Background Research and Related Work

- **Assigned to:** Abdelrahman Ayman
- **Status:** Not started
- **Main location:** `docs/research/`, `docs/final-report/references/`

### Deliverables

- [ ] Record the research question, search terms, and source-selection criteria.
- [ ] Find reliable sources about child-centered language learning, adaptive/personalized learning, and AI tutoring relevant to the approved age band.
- [ ] Compare a manageable set of existing language-learning or tutoring platforms: users, learning features, personalization, safety, and limitations.
- [ ] Review feasible AI approaches for the MVP, such as prompting an existing model and optionally retrieving from trusted learning material.
- [ ] Identify the specific gap the project will address; support claims with traceable citations.
- [ ] Summarize the research in `docs/research/literature-review.md` for Chapter 2.

## T03 — Requirements and Use Cases

- **Assigned to:** Manar Abdelrahman Mohamed
- **Status:** Not started
- **Main location:** `docs/requirements/`

### Deliverables

- [ ] **Functional requirements:** Define testable, uniquely identified requirements for the approved MVP: learner profile, goal/level, starting assessment, selected English activities, AI tutor, next-activity suggestion, and progress tracking. Include a parent/guardian summary only if approved.
- [ ] **Non-functional requirements:** Define age-appropriate interaction, privacy, security, accessibility, usability, responsive behavior, performance, and reliability expectations.
- [ ] **User roles:** Define the child learner and any approved parent/guardian or content-administrator role, including access permissions.
- [ ] **Use cases:** Document onboarding, assessment, completing an activity, asking the AI tutor for help, receiving a recommendation, and viewing progress; include preconditions, steps, alternatives, and outcomes.
- [ ] **Acceptance criteria and priorities:** Set a verifiable acceptance condition and priority for each MVP requirement.
- [ ] **Traceability:** Link objectives to requirements and planned test cases in `docs/requirements/requirements.md` and `docs/requirements/use-cases.md`.
- [ ] Review requirements with the team and supervisor; record unresolved decisions rather than assuming features.

## T04 — System Analysis and Analysis Diagrams

- **Assigned to:** Abrar Ahmed Hassan
- **Status:** Not started
- **Main location:** `docs/system-design/diagrams/`

### Deliverables

- [ ] Create a system-context diagram for the software platform and its approved users/services.
- [ ] Create a functional decomposition for the MVP features.
- [ ] Create a learner workflow from onboarding and assessment through learning activity and progress review.
- [ ] Create data-flow diagrams for the assessment, tutor request, recommendation, and progress-update flows as needed.
- [ ] Create a use-case diagram matching the approved actors and written use cases.
- [ ] Create sequence diagrams for one or two key software scenarios, such as an AI-tutor interaction and a personalized next-step recommendation.
- [ ] Explain, caption, and cross-check every diagram against the requirements; do not create hardware or robot diagrams.
- [ ] Save editable sources in `docs/system-design/diagrams/` and report-ready exports in `assets/diagrams/`.

## T05 — Software Architecture and Detailed Design

- **Assigned to:** Ahmed Mohamed Goda
- **Status:** Not started
- **Main location:** `docs/system-design/`

### Deliverables

- [ ] Design a high-level software architecture for one responsive web application.
- [ ] Define the roles of the user interface, application/API services, learning-content store, progress data, and AI/model integration where applicable.
- [ ] Design a minimal data model for learner profile, goals/level, activities, assessment results, recommendations, and progress.
- [ ] Document software interfaces, data flow, and authentication/access boundaries.
- [ ] Record the proposed technology choices and alternatives; avoid selecting multiple native clients without approval.
- [ ] Address privacy, child safety, accessibility, and model/service failure behavior in the design.
- [ ] Keep the design linked to approved requirement IDs.

## T06 — User Experience and Responsive Interface Design

- **Assigned to:** Khaled Nabil Ali Mohamed
- **Status:** Not started
- **Main location:** `docs/system-design/`, `assets/figures/`

### Deliverables

- [ ] Create simple wireframes for learner onboarding/profile, level assessment, selected lesson/activity, AI-tutor interaction, and progress view.
- [ ] Create a parent/guardian progress screen only if that feature is approved for the MVP.
- [ ] Use child-appropriate wording, navigation, visual hierarchy, and feedback for the selected age band.
- [ ] Define responsive behavior for common phone, tablet, and desktop browser widths.
- [ ] Check readability, keyboard/touch interaction, contrast, and accessibility basics.
- [ ] Keep the MVP to one responsive software interface; do not design hardware, a robot, or a Smart Mirror as deliverables.
- [ ] Save wireframes and review notes in the design folder; export approved illustrations to `assets/`.

## T07 — Learning Content and Data Management

- **Assigned to:** Melad Hani Boushra Ayad (Melad)
- **Status:** Not started
- **Main location:** `data/`, `docs/implementation/`

### Deliverables

- [ ] Identify the small set of English learning content and assessment examples required by the approved MVP.
- [ ] Record each content/data source, owner, license or permission, version, and intended learner level.
- [ ] Define a simple content/data schema, labels, validation rules, and any preprocessing steps.
- [ ] Use synthetic, public, or properly approved and de-identified learner examples; do not collect identifiable child data without institutional approval and guardian consent.
- [ ] If model evaluation or training data is needed, document a reproducible split and avoid data leakage.
- [ ] Keep large or restricted data outside Git and document its approved location in `data/external/`.

## T08 — AI Tutor and Personalization

- **Assigned to:** Melad Hani Boushra Ayad (Melad)
- **Status:** Not started
- **Main location:** `src/ml/`, `docs/implementation/`

### Deliverables

- [ ] Define the tutor's limited MVP role, supported language-learning content, input context, and expected response format.
- [ ] Evaluate an existing approved LLM/model or service; record language capability, cost/compute, privacy, and safety considerations.
- [ ] Implement prompt-based tutoring first; add retrieval from a small trusted content set only if it improves the MVP.
- [ ] Build a simple, explainable recommendation baseline using the learner's selected goal, assessment result, and progress.
- [ ] Do not train a foundation model or attempt fine-tuning/LoRA/QLoRA unless the supervisor approves a feasible data and evaluation plan.
- [ ] Evaluate answer relevance, explanation quality, age appropriateness, recommendation usefulness, and common failure cases with approved test data.
- [ ] Document model/service limits, safeguards, and fallback behavior; integrate only the approved feature with the application.

## T09 — Responsive Learning Platform Implementation

- **Assigned to:** Hossam Mohamed Abdelhakim Mohamed (Eng. Hossam) — primary; Zeinab Mohamed Ali Mohamed (Zainab) — contributor
- **Status:** Not started
- **Main location:** `src/application/`, `src/shared/`

### Deliverables

- [ ] Set up one responsive web application and document verified local build/run instructions.
- [ ] Implement the approved minimal learner profile and goal/level workflow.
- [ ] Implement the starting-level assessment and only the selected English lessons or activities.
- [ ] Integrate the approved AI tutor and next-activity recommendation component.
- [ ] Track completed activities and display a basic learner progress view.
- [ ] Implement a parent/guardian progress summary only if it is approved and fits the schedule.
- [ ] Add appropriate input validation, access control, error handling, child-safe user feedback, and automated tests.
- [ ] Verify the experience in the agreed mobile and desktop browser sizes; do not build a separate robot, Smart Mirror, or native-app client for the MVP.

## T10 — Child Safety, Privacy, and Responsible AI

- **Assigned to:** Manar Abdelrahman Mohamed
- **Status:** Not started
- **Main location:** `docs/requirements/`, `docs/testing/`

### Deliverables

- [ ] Define the minimum child data the MVP needs and avoid collecting unnecessary sensitive information.
- [ ] Document guardian consent, access control, data retention/deletion, and test-data rules required by the institution.
- [ ] Define age-appropriate response and content requirements for the AI tutor, including unsafe, misleading, or out-of-scope requests.
- [ ] Make clear that the AI feature is educational support and not a replacement for a parent, teacher, or qualified professional.
- [ ] Define review and fallback behavior when the model produces an unsuitable or uncertain answer.
- [ ] Create privacy and safety test scenarios; use synthetic accounts unless real-user testing is formally approved.
- [ ] Record unresolved ethical, legal, and institutional questions for supervisor review.

## T11 — Testing and Validation

- **Assigned to:** Ahmed Mohamed Goda — primary; Khaled Nabil Ali Mohamed — responsive-UX test support
- **Status:** Not started
- **Main location:** `tests/`, `docs/testing/`

### Deliverables

- [ ] Create a test plan linked to requirement IDs and MVP acceptance criteria.
- [ ] Add unit tests for important application, assessment, progress, and recommendation logic.
- [ ] Add integration tests for the application, data store, and AI/model interface where applicable.
- [ ] Test learner scenarios from goal/assessment through activity completion and progress update.
- [ ] Test responsive layouts on the agreed common browser/device-size matrix.
- [ ] Evaluate AI-tutor responses and recommendations for relevance, age appropriateness, safety, and failure handling using approved sample data.
- [ ] Record test environment, steps, expected/actual results, pass/fail status, defects, retests, and evidence.
- [ ] Do not test with real children unless the institution approves the method and required guardian consent is in place.

## T12 — Final Report: Introduction and Related Work

- **Assigned to:** Abdelrahman Ayman
- **Status:** Not started
- **Main location:** `docs/final-report/chapters/`

### Deliverables

- [ ] Complete Chapter 1 with the project context, problem, MVP scope, constraints, objectives, methodology, impact, and key terms.
- [ ] Explain the initial target age band and English-learning focus once approved; distinguish the MVP from the long-term ecosystem vision.
- [ ] Complete Chapter 2 with relevant child-centered learning, language-learning, AI-tutoring background, related systems, comparison, and project gap.
- [ ] Support factual claims with reliable, traceable sources.
- [ ] Save drafts in the Chapter 1 and Chapter 2 files and request team/supervisor review.

## T13 — Final Report: System Analysis and Design

- **Assigned to:** Abrar Ahmed Hassan
- **Status:** Not started
- **Main location:** `docs/final-report/chapters/`

### Deliverables

- [ ] Complete Chapter 3 with approved actors, MVP requirements, use cases, learner workflow, and relevant software-analysis diagrams.
- [ ] Complete Chapter 4 with responsive software architecture, data model, interfaces, wireframes, and AI/personalization design actually in scope.
- [ ] Ensure each diagram is readable, explained, captioned, and consistent with the final requirements.
- [ ] Do not include hardware, robot, or Smart Mirror implementation designs in the MVP chapters.
- [ ] Save drafts in the Chapter 3 and Chapter 4 files and request team/supervisor review.

## T14 — Final Report: Implementation, Conclusion, and Appendices

- **Assigned to:** Zeinab Mohamed Ali Mohamed (Zainab)
- **Status:** Not started
- **Main location:** `docs/final-report/chapters/`, `docs/final-report/appendices/`

### Deliverables

- [ ] Complete Chapter 5 with the verified software stack, implemented web features, AI-tutor/personalization integration, and clear screenshots.
- [ ] Report actual test/evaluation results and link them to project objectives and test records.
- [ ] Complete Chapter 6 with achieved objectives, limitations, and realistic future work.
- [ ] Treat other development pillars, robot, and Smart Mirror as future vision unless the approved scope changes.
- [ ] Add only relevant appendices, such as setup instructions, selected code listings, or test material.
- [ ] Remove private data, unsupported claims, and unused placeholders before review.

## T15 — References, Figures, and Final Report Quality Review

- **Assigned to:** Khaled Nabil Ali Mohamed
- **Status:** Not started
- **Main location:** `docs/final-report/`, `assets/`

### Deliverables

- [ ] Ensure every in-text citation has a matching reference and every listed source is used.
- [ ] Apply the citation style, language, page layout, and formatting required by the institute.
- [ ] Generate the final table of contents and list of figures from the finished document; update page numbers.
- [ ] Check chapter/section/figure numbering, captions, screenshot readability, spelling, grammar, and consistent terminology.
- [ ] Resolve every `[TODO]`, sample name, old example, broken link, or unapproved feature claim.
- [ ] Obtain team and supervisor review and prepare the required submission format.

## T16 — Presentation and Software Demonstration

- **Assigned to:** Zeinab Mohamed Ali Mohamed (Zainab) — coordinator; all team members contribute
- **Status:** Not started
- **Main location:** `docs/presentation/`, `assets/`

### Deliverables

- [ ] Prepare slides covering the child-development vision, the deliberately limited MVP, target learners, problem, solution, software architecture, and evaluation results.
- [ ] Demonstrate the responsive English-learning workflow and the AI tutor/recommendation feature actually implemented.
- [ ] Use a verified demo account and synthetic or otherwise approved non-sensitive sample data.
- [ ] Prepare backup screenshots or a recording in case the live software demonstration fails.
- [ ] Divide speaking roles among the team and rehearse the complete presentation and demonstration.
- [ ] Ensure the presentation distinguishes completed MVP features from future ideas such as the robot, Smart Mirror, other pillars, or custom LLM training.
