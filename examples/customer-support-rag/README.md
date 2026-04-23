# Example: Customer Support RAG

This is a compact example of how to apply the workflow to a familiar AI use case.

## Purpose

Use an internal-policy retrieval assistant to help support staff answer customer questions faster without allowing the AI to make binding decisions on refunds, complaints, or legal exceptions.

## In-scope decisions

- whether a question can be answered from approved policy material
- whether the prompt should be blocked, redacted, or routed onward
- which approved knowledge sources can be used
- whether a response is only advisory or must go to human review

## Out-of-scope decisions

- final approval of refunds
- legal interpretation for edge cases
- account changes
- customer identity verification

## Example controls

- Named support purpose with an approved knowledge corpus.
- Machine identity for the calling workload.
- Policy check before retrieval or model call.
- PII-aware prompt handling.
- Clear branch to human queue for exceptions.
- Signed or otherwise integrity-protected evidence for the decision trail.

## Example proof artefacts

- approved purpose definition
- source corpus inventory
- access policy and review record
- runtime request log with decision outcome
- human escalation record
- incident and fallback handling notes

This example is intentionally small. Its job is to show the shape of a GAD case, not to replace a full engagement.
