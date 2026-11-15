# Personal Task Checklist — Melad Hani Boushra Ayad

- **Preferred name:** Melad
- **Assigned task IDs:** T07, T08
- **Assignment status:** Provisional; the team may change owners or scope.

Use this file to track your work. The master `TASK_ASSIGNMENTS.md` is the source of truth; keep both files consistent if a task changes. Check each deliverable only after saving it in the listed project location and having it reviewed.

## Your assigned task checklists

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

## Shared contribution to T16 — Presentation and Software Demonstration

Zeinab coordinates T16, but every team member contributes.

- [ ] Prepare a concise explanation of your assigned work and what was actually completed.
- [ ] Provide approved screenshots, diagrams, test evidence, or references from your tasks for the presentation.
- [ ] Coordinate your speaking/demo contribution with Zeinab and attend the team rehearsal.
- [ ] Use only synthetic or otherwise approved non-sensitive demo data.
