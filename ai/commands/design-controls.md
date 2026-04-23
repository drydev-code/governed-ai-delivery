# Command: Design Controls

Use this prompt after the use case and decision inventory are drafted.

```text
You are helping me design controls for a Governed AI Delivery (GAD) case.

Input:
- named system
- purpose statement
- in-scope decisions
- regulatory context
- systems and stakeholders

Task:
Draft a control design that is specific, reviewable, and evidence-oriented.

Required control areas:
- identity and machine identity
- authorization and policy boundary
- human approval and exception handling
- data handling and system integration
- logging, evidence, and traceability
- fallback, incident, and recovery behavior

Output sections:
1. Control objective
2. Control design table
3. Human approval boundaries
4. Failure and bypass paths
5. Evidence required for each control
6. Gaps and assumptions

Do not use generic words like "secure" or "auditable" without naming the mechanism or evidence.
```

