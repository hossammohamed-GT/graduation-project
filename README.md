# Intelligent Learning and Growth Platform

**Broader vision in the supplied concept brief:** *AI-Powered Child Development Ecosystem — An Intelligent Ecosystem for Learning, Personal Growth, and Child Development.* Confirm the final cover-page title with the supervisor; the repository keeps the title previously provided by the team for now.

This repository is the shared workspace for planning and delivering a **software-only child-development platform**. The long-term vision is broad, but the recommended graduation-project MVP is deliberately smaller: one responsive web application, with the English Language Learning System as its first subsystem for one age group selected with the supervisor.

## Proposed first version

- A responsive browser-based experience usable on common phones, tablets, and desktop screens; do not build separate native apps for every device in the MVP.
- A learner profile with minimal necessary information and a starting-level assessment.
- A limited set of English-learning activities selected by the team, such as vocabulary and grammar practice.
- An AI tutor using an existing model/service, with age-appropriate prompts and a small trusted content set where useful.
- Simple personalized next-step recommendations, progress tracking, and a basic learning plan.
- A parent/guardian progress summary only if time and approved scope allow.

The robot, Smart Mirror, hardware, voice/camera interfaces, full academic curriculum, all four development pillars, a comprehensive parent dashboard, and custom LLM training are long-term ideas—not current MVP commitments. See `docs/planning/project-overview.md` and `TASK_ASSIGNMENTS.md` for the scope boundary.

## How to use this repository

1. Review `TASK_ASSIGNMENTS.md`; its owners are provisional and can be changed by the team.
2. Confirm the official project title, first age group, MVP features, and evaluation approach with the supervisor.
3. Record approved decisions in `docs/planning/project-charter.md` and `docs/planning/project-overview.md`.
4. Keep research, requirements, design, testing evidence, and report chapters in their dedicated folders.
5. Put software source code in `src/`, approved datasets or learning content in `data/`, and report-ready media in `assets/`.
6. Update task checklists and status when deliverables have been reviewed.

## Repository map

| Path | Purpose |
| --- | --- |
| `TASK_ASSIGNMENTS.md` | Provisional team assignments and detailed deliverable checklists for all work packages. |
| `team/` | Team roster and per-member task breakdowns. |
| `docs/` | Planning, research, requirements, system design, implementation, testing, final report, and presentation material. |
| `src/` | Software application, AI/ML, and shared source modules. |
| `data/` | Dataset and learning-content organization. Do not commit private, unapproved, or very large data. |
| `assets/` | Reusable diagrams, figures, and screenshots for reports and presentations. |
| `tests/` | Automated unit, integration, and system tests. |
| `tools/` | Reusable development, data, build, or documentation utilities. |

Every project directory contains a `README.md` describing what belongs there. The repository currently provides structure and writing templates; implementation details remain subject to the approved scope.

## Working conventions

- Use English for repository documentation, folder names, task descriptions, and code comments.
- Use descriptive `kebab-case` names, such as `system-architecture.md`.
- Keep original evidence separate from edited, report-ready assets.
- Cite external material and record its bibliographic details in `docs/final-report/references/`.
- Do not commit credentials, private contact details, identifiable child data, or generated build output.
- Follow the institute's formatting guide when one is provided; this repository does not assume a font, margin size, or required export format.
