---
type: decision-card
status: template-ready
package: "[[../../Generated-Packages/Markdown Review Control Plane/README|Markdown Review Control Plane]]"
github_repo: "https://github.com/vinayclawagent-art/markdown-review-control-plane"
created: 2026-06-09
tags: [promotion-decision, markdown-review, evidence-pending]
---

# Promotion Decision Card: Markdown Review Control Plane

Fill this **after** the First Real Trial Packet has real before/after markdown, comment export, patch diff, and reviewer notes. This card is ready for the next real trial; it is not validation proof.

## Evidence prerequisites

- [ ] First Real Trial Packet is filled with a real markdown review workflow.
- [ ] Before markdown is linked or pasted.
- [ ] Comment/export JSON or structured notes are attached.
- [ ] Patch diff is attached.
- [ ] Human reviewer outcome is recorded.

## Trial result summary

- Trial date:
- File reviewed:
- Number of comments:
- Number of comments resolved into accepted edits:
- Time from comment to merged patch:
- Reviewer confidence (1-5):
- Biggest failure mode:

## Promotion rubric

| Criterion | Promote | Pilot-only | Iterate | Hold |
| --- | --- | --- | --- | --- |
| Comments map cleanly to markdown ranges |  |  |  |  |
| Agent handoff produces useful patches |  |  |  |  |
| Review state stays git-readable |  |  |  |  |
| Workflow beats ad hoc Docs/PR review |  |  |  |  |
| Skill draft has clear repeatable triggers |  |  |  |  |

## Decision

Choose one:

- [ ] **Promote skill** after a second clean run confirms repeatability.
- [ ] **Keep as project pilot** for X-Intel artifact README reviews only.
- [ ] **Iterate prototype** before another trial.
- [ ] **Hold** until stronger demand appears.

## Required follow-up

- Prototype update:
- Package README update:
- Skill draft update:
- Next markdown file to test:
