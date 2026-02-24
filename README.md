# Joy Copilot Training Content (Repository Root)

This repository contains curated training content for the Joy Loyalty AI Copilot, designed to help customer support agents and to serve as training material for the assistant.

Repository layout

- `FAQ/` — Topic-based Q&A files. Each file contains at least 5 sample question-and-answer pairs to help the assistant respond to common user questions.
- `templates/` — Documentation templates used for authoring features and troubleshooting guides:
  - `TEMPLATE-feature.md`
  - `TEMPLATE-troubleshooting.md`
- `training-data/` — Core training artifacts:
  - `system-prompt.md` — Instructional prompt to guide assistant behavior and tone.
  - `knowledge-base.md` — Concise product knowledge summary.

Contribution guide

1. Add new topics: Create a new markdown file under `FAQ/` named with the topic (e.g., `billing.md`) and include at least 5 well-formed Q&A items.
2. Use templates: When adding feature or troubleshooting docs, use the files under `templates/` to ensure consistent structure.
3. Keep content in English and avoid including PII or secrets in any file.
4. Proofread entries for clarity and correctness; factual accuracy is critical.
5. For major updates to `training-data/knowledge-base.md`, include a short changelog entry at the top of the file.

Quality checklist for PRs

- [ ] Content is factual and up-to-date.
- [ ] No sensitive data included.
- [ ] Follows template structure where applicable.
- [ ] Includes links to related FAQ or product docs when relevant.

If you want, I can add an automated content linter or a GitHub Action to validate new FAQ files. Specify if you'd like that next.