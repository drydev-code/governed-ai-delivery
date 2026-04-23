# Governed AI Delivery

Governed AI Delivery (GAD) is a control-first approach for putting AI into production where security, auditability, and regulation matter.

This repository is the public home of the approach:

- it explains GAD without assuming prior context
- it gives you a small, repeatable workflow to apply the approach
- it includes templates, examples, and AI-assistance assets you can use immediately

The short version of GAD is:

1. Map the real use case.
2. Design the controls before touching the model.
3. Integrate the AI under those controls.
4. Prove what happened with usable evidence.

## Why this repo exists

This repo is meant to be understandable and usable from the outside.

Use it when you want to answer questions like:

- What exactly is the AI allowed to do?
- Which decisions stay human?
- Which identities, approvals, and logs are required?
- What evidence do we need for security, audit, or regulators?
- How do we make an AI assistant help without drifting into vague advice?

## What is here

- [docs/01-what-is-gad.md](docs/01-what-is-gad.md): the core idea and boundaries
- [docs/02-quickstart.md](docs/02-quickstart.md): the fastest way to apply GAD on a real case
- [docs/03-workflow.md](docs/03-workflow.md): the working cycle and expected outputs
- [templates/engagement/](templates/engagement/): the base artefacts for a real engagement
- [examples/customer-support-rag/](examples/customer-support-rag/): a compact worked example
- [ai/README.md](ai/README.md): how to use AI assistance safely and productively
- [ai/commands/](ai/commands/): reusable prompts for mapping, control design, and challenge review
- [ai/skills/gad-facilitator/SKILL.md](ai/skills/gad-facilitator/SKILL.md): a portable skill or instruction file for AI copilots
- [AGENTS.md](AGENTS.md): repo-wide guidance for AI assistants working in this repository

## Fast start

1. Read [docs/01-what-is-gad.md](docs/01-what-is-gad.md).
2. Copy [templates/engagement/](templates/engagement/) into a new folder such as `cases/my-system/`.
3. Work through the files in order from `01-use-case.md` to `06-proof-pack.md`.
4. Use the prompts in [ai/commands/](ai/commands/) to have an AI assistant draft, critique, and tighten each artefact.
5. Keep only claims you can tie to a real system, owner, control, or evidence source.

## What good looks like

A GAD engagement is in decent shape when you can answer all of these clearly:

- What named purpose is the AI serving?
- Which business decisions are in scope?
- Which regulations or internal obligations matter?
- Which identities, policies, approvals, and fallback paths exist?
- Which systems and data flows are touched?
- Which evidence would let an auditor, CISO, or customer inspect the design later?

## Scope boundary

This repo helps with governed production AI. It does not replace:

- legal advice
- formal conformity assessment
- an ISMS
- model-quality evaluation
- general software delivery discipline

It is the operational layer that turns AI governance from slides into design artefacts and proof.

## Examples and cases

This public repo contains compact example material, but not internal customer or company cases.

Use the templates here to create your own case folders and evidence trail.
