# Christopher Schafrath

I build intelligent operational systems for small businesses.

They recover revenue, remove administrative drag, and turn fragmented information into action. Each repository below is a complete, independently runnable system — not a slice of a shared platform, and not an LLM wrapped in a UI.

A prospective client should recognize the operating problem. A hiring manager should see product judgment plus complete systems execution. An engineer should be able to inspect state, authority boundaries, failure handling, evaluation, and proof.

## Revenue Rescue

[Recover high-intent HVAC inbound](https://github.com/ambientframe/revenue-rescue) before slow response or a missed SLA burns the job.

After-hours demand is classified, acknowledged once, routed, and escalated on the SLA clock. Replay cannot send a second customer-visible text. Humans keep discard, resolve, and forced-route authority.

Inspect: [README](https://github.com/ambientframe/revenue-rescue) · [proof](https://github.com/ambientframe/revenue-rescue/blob/master/proof/report.md) · [domain](https://github.com/ambientframe/revenue-rescue/tree/master/lib/domain)

## Client Intake Operator

[Turn messy remodeling intake into reviewable work](https://github.com/ambientframe/client-intake-operator), or keep it blocked until a person settles the evidence.

Form, follow-up email, and site worksheet are merged with field-level provenance. Budget/scope contradictions and missing contact stay visible. Only human approval writes an authoritative job file.

Inspect: [README](https://github.com/ambientframe/client-intake-operator) · [proof](https://github.com/ambientframe/client-intake-operator/blob/master/proof/report.md) · [domain](https://github.com/ambientframe/client-intake-operator/tree/master/lib/domain)

## Cashflow Operator

[Reduce overdue-invoice follow-up drag](https://github.com/ambientframe/cashflow-operator) without inventing collection policy or threatening customers.

A temporal policy function decides the next permitted notice, waits, and stops on payment or dispute. Send keys are replay-safe. High-value balances and disputes go to a human.

Inspect: [README](https://github.com/ambientframe/cashflow-operator) · [proof](https://github.com/ambientframe/cashflow-operator/blob/master/proof/report.md) · [domain](https://github.com/ambientframe/cashflow-operator/tree/master/lib/domain)

## Owner Intelligence

[Turn fragmented clinic records into prioritized action](https://github.com/ambientframe/owner-intelligence) a specialty-practice owner can stand behind.

The morning brief ranks what changed and why, cites record ids, and flags stale or conflicting evidence. It cannot move money, mutate the schedule, or message clients.

Inspect: [README](https://github.com/ambientframe/owner-intelligence) · [proof](https://github.com/ambientframe/owner-intelligence/blob/master/proof/report.md) · [domain](https://github.com/ambientframe/owner-intelligence/tree/master/lib/domain)

## How the work is built

Record authoritative state. Encode policy deterministically when the rule is known. Bound model judgment to a schema when inference is useful. Keep humans in authority for consequence. Attach provenance. Make recovery and replay safe. Evaluate the failure modes that would actually hurt the business.

Default demos run locally against synthetic fixtures. Maturity across all four is **fixture-backed + internally tested + browser-verified**. No production customers, live business integrations, or paid-model operation are claimed here. Proof lives in each repository’s `proof/` directory.
