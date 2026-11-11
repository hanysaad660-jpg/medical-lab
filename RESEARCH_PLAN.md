# Research Plan | November 2026 – October 2027

## Purpose

Explore practical, testable software approaches for safer and more maintainable clinical laboratory information workflows. The work is engineering research, not a clinical trial or a claim that the software is ready for patient care.

## Questions and hypotheses

**RQ1 — Identity and traceability.** Can explicit identifiers and event histories reduce ambiguity between a patient's record, repeated orders, specimens, and result versions in a laboratory workflow model?

**RQ2 — Reliability under failure.** Can transaction boundaries, idempotent processing, audit trails, and recovery tests help preserve data integrity when messages are duplicated, delayed, interrupted, or arrive out of order?

**RQ3 — Adaptability.** Can configurable, server-governed data definitions and shared interfaces support different institutional and linguistic needs without duplicating core clinical rules?

These are hypotheses to evaluate, not outcomes already demonstrated.

## Planned work

| Period | Priority | Planned evidence or output |
| --- | --- | --- |
| Months 1–3 (Nov 2026–Jan 2027) | Consolidate research questions, identity models, and scenario inventory | Traceability diagrams, standards crosswalk, synthetic-data test cases |
| Months 4–6 (Feb–Apr 2027) | Investigate order and specimen lifecycle models | Reviewed workflow definitions, negative-path and duplicate-event test reports |
| Months 7–9 (May–Jul 2027) | Examine result versioning, correction, authorization, and interoperability boundaries | Prototype demonstrations using synthetic data and design decision records |
| Months 10–12 (Aug–Oct 2027) | Repeat evaluation, review limitations, and publish safe findings | Evaluation summary, technical notes, revised roadmap and research artifact index |

Dates are targets, not promises. Scope and sequencing may change if safety or technical evaluation reveals unresolved problems.

## How AI-assisted tools may help

Tools such as Google Antigravity may help organize public references, compare design alternatives, navigate large codebases, draft non-confidential technical notes, and generate candidate test scenarios. AI outputs will not be treated as verified research evidence, and security-sensitive and clinically relevant decisions will require independent review.

## Deliverables

1. A maintained public research description and evidence-based workflow documentation.
2. A privately developed research prototype for structured technical evaluation.
3. Reproducible synthetic-data scenarios and summary test results, published only where disclosure is safe.
4. Public technical notes on design decisions, risks, negative findings, and next steps.

**Not promised:** peer-reviewed publication, public release of the application source code, clinical deployment, certification, or demonstrated patient outcomes.
