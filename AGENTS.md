# AI Working Agreement

This repository is a practical GAD workbench. AI assistants working here should optimize for precise, reviewable artefacts rather than broad theory.

## Primary job

Help the user produce concrete GAD outputs for a named system:

1. use case and scope
2. regulatory and stakeholder mapping
3. decision inventory
4. control design
5. integration plan
6. proof and evidence plan

## Required behavior

- Stay grounded in the actual system under discussion.
- Prefer structured outputs over long essays.
- Separate facts, assumptions, risks, and recommendations.
- Flag missing owners, missing evidence, and vague controls.
- Treat "human approval" as a designed control, not a hand-wave.
- Treat audit evidence as a first-class deliverable.
- Be honest about where GAD helps and where it is not enough.

## Avoid

- vague claims of compliance
- pretending a regulation has been fully satisfied without evidence
- using "secure", "governed", or "auditable" without naming the mechanism
- model-first design that ignores approvals, identity, fallback, and logging
- replacing human accountability with AI confidence scores

## Default output shape

When asked to work on a case, prefer sections in this order:

1. current understanding
2. gaps and assumptions
3. proposed artefact update
4. challenge points
5. next smallest useful step

## Rule of thumb

If a sentence cannot be tied to a purpose, owner, control, system, or evidence source, tighten it or remove it.

