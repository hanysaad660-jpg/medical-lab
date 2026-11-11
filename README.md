# MedicalLab-Core | Laboratory Informatics Research

**Independent research and software engineering project**  
**Focus:** safer laboratory workflows, patient identity, data integrity, and interoperability  
**Research period:** November 2026 – October 2027 (planned)  
**Status:** exploratory research and prototype development; not clinically deployed

Medical laboratories depend on reliable information systems to connect a patient, a test request, a specimen, and a reported result. Mistakes in identification or workflow tracking can be difficult to detect after they have moved between people and systems. MedicalLab-Core is an independent research and development project exploring how to make these connections clearer, more traceable, and easier to verify in laboratory software.

This repository is a **public description of the research project**. It does not contain the application's source code, patient records, credentials, or deployment materials. The working software is developed separately.

## Research questions

1. How can laboratory software preserve a clear, auditable relationship between patient identity, orders, specimens, and repeat test results?
2. Which architectural and testing practices can reduce preventable workflow errors while keeping modules maintainable and interoperable?
3. How can the same underlying clinical rules support Arabic and English interfaces, as well as deployment in different institutional settings?

## Approach

The project combines reviews of established laboratory information systems and published healthcare standards with domain modelling, iterative prototyping, and repeatable software tests. The reference implementation is being explored with **C#, .NET 10, PostgreSQL, web interfaces, and Windows desktop interfaces**, following a modular-monolith design. Testing uses synthetic records rather than identifiable patient data.

The work is informed by the WHO Laboratory Quality Management System handbook, ISO 15189:2022, HL7 FHIR, and IHE laboratory integration guidance where relevant. **These are references for research and design, not claims of certification, conformance, accreditation, or clinical validation.**

## Expected outputs, next 6–12 months

- Documented workflow and identity models for patient registration, test orders, specimens, and result traceability.
- A research prototype that can be evaluated against clearly stated technical and workflow scenarios.
- A reproducible synthetic-data test plan covering access controls, audit trails, retries, duplicate events, language support, and recovery.
- Public technical notes describing design choices, limitations, and lessons learned, without exposing proprietary code or sensitive data.

## Read the project documents

| Document | Purpose |
| --- | --- |
| [Research abstract](RESEARCH_ABSTRACT.md) | A concise, public-level description suitable for a research overview. |
| [Research plan](RESEARCH_PLAN.md) | Questions, milestones, and intended deliverables for the next year. |
| [Methodology](METHODOLOGY.md) | Evidence review, design, and evaluation approach. |
| [Project status](PROJECT_STATUS.md) | Current boundaries, limitations, and what is not yet established. |
| [Privacy and responsible research](PRIVACY_AND_SAFETY.md) | How sensitive information and claims are handled. |

## Research independence and contact

This is an **independent project**, not an officially affiliated university research group, accredited medical laboratory, or government initiative. Institutional collaborators, if any, should be identified only after they are formally confirmed. For public project information, use this repository and its owner's GitHub profile.

## References

- [WHO — Laboratory quality management system: handbook](https://www.who.int/publications/i/item/9789241548274)
- [ISO — ISO 15189:2022, Medical laboratories — Requirements for quality and competence](https://www.iso.org/standard/76677.html)
- [HL7 — FHIR specification](https://hl7.org/fhir/)
- [IHE — Technical frameworks and laboratory integration guidance](https://profiles.ihe.net/)

*Documentation prepared for public research communication. No source-code license or permission to reuse the private application is granted by this repository.*
