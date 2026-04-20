# Control Catalog

## Purpose

This document defines the control areas used in the **AI Use-Case Governance Registry** repository.

Its purpose is to provide a simple reference point for control review. It supports consistent review across use cases without presenting the repository as a formal compliance framework.

This document aligns with concepts used in the EU AI Act, NIST AI RMF 1.0, and ISO/IEC 42001. It does **not** constitute legal advice, formal compliance determination, conformity assessment, or certification.

## Scope

This catalog is used during the control review stage of the repository workflow.

It is intended to support a simple review of whether key governance measures are:

- applicable
- already in place
- planned
- unclear
- not applicable

The catalog is intentionally high level. It does not attempt to reproduce full legal or standards requirements.

## How to use this catalog

### Framework requirement

The source frameworks support documented governance, accountability, risk management, monitoring, and review.

### Recommended practice

A repository-level governance process should use a stable set of control areas so that reviews are comparable across use cases.

### Inference

For this project, a concise control catalog is sufficient. The catalog should support structured review without turning the repository into a detailed control implementation program.

## Control areas

### 1. Governance and accountability

**Objective**  
Ensure that ownership, responsibility, and review accountability are defined.

**Example review questions**
- Is there a clearly identified use case owner?
- Is governance review ownership defined?
- Are escalation points identified where needed?

### 2. Documentation and recordkeeping

**Objective**  
Ensure that the use case, its purpose, and governance decisions are documented and traceable.

**Example review questions**
- Is the use case record complete enough for review?
- Is the impact assessment documented?
- Is the classification rationale recorded?
- Is the decision traceable?

### 3. Human oversight

**Objective**  
Ensure that human involvement and oversight expectations are considered where relevant.

**Example review questions**
- Is human review part of the process where appropriate?
- Are there clear points for intervention or override?
- Are human responsibilities defined?

### 4. Transparency and communication

**Objective**  
Ensure that relevant transparency considerations are identified.

**Example review questions**
- Is the role of the AI system communicated appropriately?
- Are users or affected persons likely to need additional explanation?
- Are significant limitations documented?

### 5. Data governance

**Objective**  
Ensure that data-related governance considerations are identified.

**Example review questions**
- Are relevant data sources identified?
- Are sensitive data considerations documented?
- Are data limitations or quality concerns noted?

### 6. Technical robustness and reliability

**Objective**  
Ensure that reliability, fitness for purpose, and operational limitations are considered.

**Example review questions**
- Are known limitations documented?
- Is the system sufficiently stable for the intended context?
- Are reliability concerns identified for follow-up?

### 7. Security and resilience

**Objective**  
Ensure that relevant security and resilience concerns are considered.

**Example review questions**
- Are material security concerns identified?
- Are dependencies on third-party systems or providers understood?
- Are failure or misuse concerns documented?

### 8. Monitoring and review

**Objective**  
Ensure that the use case has a basis for follow-up review after the initial governance decision.

**Example review questions**
- Is a review date or trigger recorded?
- Are material change triggers identified?
- Is there a basis for reassessment if the use case changes?

## Control review status model

The repository uses the following status values during control review:

- `not_started`
- `planned`
- `partially_in_place`
- `in_place`
- `not_applicable`
- `unclear`

These values are intended to support governance review only. They are not maturity ratings and do not establish compliance status.

## Control selection principle

Not every control area will apply in the same way to every use case.

### Framework requirement

The source frameworks support context-based and risk-based governance rather than identical treatment for all systems.

### Recommended practice

Control applicability should be determined in relation to intended purpose, deployment context, affected stakeholders, and identified impacts.

### Inference

For this repository, control review should remain lightweight but should still record why a control area is applicable, unclear, or not applicable.

## Relationship to source frameworks

### EU AI Act

This catalog reflects a risk-based governance mindset. It should not be read as a statement that satisfying these control areas is sufficient for legal compliance under the AI Act. Any legal analysis would require a separate assessment.

### NIST AI RMF 1.0

This catalog is broadly consistent with NIST AI RMF themes such as governance, context, measurement, management, and trustworthiness considerations. It is not a checklist implementation of NIST AI RMF.

### ISO/IEC 42001

This catalog is broadly consistent with a management-system approach that includes documented governance, assigned responsibilities, controls, monitoring, and continual improvement. It does not claim conformity with ISO/IEC 42001.

## Design limitations

This control catalog does **not**:

- define mandatory enterprise controls
- create a detailed implementation standard
- replace legal, compliance, privacy, security, or audit review
- determine AI Act obligations
- certify ISO/IEC 42001 alignment
- implement NIST AI RMF as a checklist

## Summary

This control catalog gives the repository a stable structure for control review.

It is designed to support:

- consistent review across use cases
- traceable governance decisions
- context-based control applicability
- linkage between classification and review
