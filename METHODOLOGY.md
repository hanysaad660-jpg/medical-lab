# Research Methodology

This document explains how the project intends to distinguish promising ideas from demonstrated results.

## 1. Review and comparison

- Examine public documentation and, where legally available, source implementations of established laboratory information systems.
- Track each significant design conclusion to its source, including product or standard version and publication date when available.
- Separate normative requirements, common implementation practices, project hypotheses, and unverified opinions.
- Check licensing and permitted reuse before adapting any third-party material. No external implementation is assumed appropriate without evaluation.

## 2. Design and prototyping

Investigate modular boundaries for patient identity, organization structure, test catalogues, orders, specimens, results, audit, and integrations. Keep clinical decisions and access controls authoritative on the server rather than duplicating them in web and desktop interfaces. Model identifiers and result histories explicitly so corrected or repeated results remain distinguishable.

## 3. Evaluation using synthetic records

Test plans are expected to include ordinary workflow examples and failure cases, such as:

- two patients with similar names, and multiple identifiers for one patient;
- repeated tests and result revisions that must remain distinguishable;
- cross-organization access attempts and permission changes;
- interrupted requests, retried operations, and duplicate or out-of-order events;
- Arabic and English entry, display, search, and mixed-direction text;
- restart, recovery, and consistency checks.

The goal is to record what was tested, under which conditions, and whether the outcome was reproduced. A passing test in a local synthetic environment is not proof of safety in a live laboratory.

## 4. Evidence rules

A claim will be labelled as one of: **planned**, **implemented locally**, **tested on synthetic data**, **externally reviewed**, or **clinically validated**. The project will not use a higher evidence label without corresponding records. Conflicting evidence and unsuccessful tests will be retained in the research record instead of silently dropped.

## 5. Standards and guidance

The project may draw on the WHO Laboratory Quality Management System handbook, ISO 15189:2022, HL7 FHIR, and IHE technical frameworks where applicable. Applicability to a particular feature must be checked case by case; merely consulting a standard does not establish compliance. Any future production deployment would require its own regulatory, clinical, cybersecurity, and operational assessments.

See [README](README.md) for links to the relevant issuing organizations.
