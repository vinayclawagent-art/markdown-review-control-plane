---
name: markdown-review-control-plane
description: "Draft skill from X Artifact Factory: Capture unresolved markdown comments, route them into agent-editable patch requests, and record resolved decisions back into git-readable notes."
version: 0.1.0
status: draft
---

# Markdown Review Control Plane Skill Draft

## Trigger
Use when a task needs this repeatable workflow: Capture unresolved markdown comments, route them into agent-editable patch requests, and record resolved decisions back into git-readable notes.

## Steps
1. Identify the source artifact, screen, markdown file, or dataset.
2. Capture the smallest bounded context needed for an agent to act.
3. Generate a task packet with acceptance criteria and evidence requirements.
4. Run the workflow on one real example.
5. Record output, unresolved risks, and a promote / iterate / hold decision.

## Pitfalls
- Do not claim validation before a real trial exists.
- Keep the first workflow narrow; avoid turning the kit into a broad platform.
- Preserve source links back to the X-Intel note and artifact package.

## Promotion criteria
Promote only after two clean real runs produce useful artifacts without duplicating an installed Hermes skill.
