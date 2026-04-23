# What GAD Is

GAD is a delivery approach for production AI in environments where someone will eventually ask:

- who approved this
- which identity acted
- what data was touched
- what the AI was allowed to do
- what happened when something went wrong
- how any of that can be proven later

The method is intentionally simple:

1. `Map`
   Understand the use case, the in-scope decisions, the systems, the data, the owners, and the regulatory surface.
2. `Design`
   Define identities, policies, approvals, exception paths, logging, and proof before implementation.
3. `Integrate`
   Connect the AI into the real environment under those controls.
4. `Prove`
   Produce evidence that makes the design inspectable and the operation reviewable.

## What GAD focuses on

GAD is strongest where AI touches:

- regulated processes
- customer-impacting decisions
- security-relevant workflows
- legacy systems
- approval chains
- audit or incident response requirements

## What GAD is not

GAD is not:

- a replacement for legal advice
- a shortcut to claiming compliance
- a pure model-evaluation method
- a general prompt-engineering framework
- a governance deck without implementation consequences

## The core design stance

GAD starts from control questions, not model excitement.

The useful shift is:

- from "Which model should we use?"
- to "What is this AI allowed to do, under whose authority, with which controls, and how will we prove it?"

## The minimum artefacts

A lightweight but real GAD pass should produce:

- a named use case
- a decision inventory
- a regulation and stakeholder map
- a control design
- an integration plan
- a proof pack

That is enough to move from fuzzy intent to something a delivery team, security lead, or auditor can actually inspect.

