# Classification Rules

This document defines the classification rules used in the **AI Use-Case Governance Registry** repository.

Its purpose is to support a consistent **preliminary governance classification** for AI use cases before control review and governance decision.

These rules align with concepts used in the EU AI Act, NIST AI RMF 1.0, and ISO/IEC 42001. They do **not** constitute legal advice or formal legal classification under the EU AI Act.

## Scope

These rules are used to support the `schema/classification.yaml` record.

They are intended to help reviewers determine whether a use case appears to require:

- limited governance attention
- further review
- escalation due to higher-risk context
- concern about a potentially prohibited use
- explicit recording that classification remains unclear


## Classification principle

### Framework requirement

The source frameworks support context-based and risk-based review rather than identical treatment of all AI systems.

### Recommended practice

Classification should be based on intended purpose, deployment context, affected persons, decision influence, and potential impact.

### Inference

For this repository, classification should remain simple, documented, and explicitly preliminary.

## Required inputs

A classification should not be recorded without, at minimum:

- a use case record
- an impact assessment
- a description of intended purpose
- a description of deployment context
- identified affected persons or groups
- a short rationale for the classification

If these inputs are missing, the appropriate result is normally `classification_unclear`.

## Classification labels

The repository uses the following governance classification labels:

- `minimal_risk_or_limited_governance_attention`
- `requires_further_review`
- `higher_risk_context_possible`
- `prohibited_use_case_concern`
- `classification_unclear`

These labels are repository-level governance labels. They are not legal categories under the EU AI Act.

## Rule set

### 1. minimal_risk_or_limited_governance_attention

Use this label when all of the following are true:

- the intended purpose is reasonably clear
- the deployment context appears limited in impact
- the use case does not appear to materially influence important decisions about individuals
- no significant concern has been identified regarding affected persons, safety, fundamental rights, or similar high-impact outcomes
- no strong reason for escalation has been identified

This label does **not** mean “no risk.” It means limited governance attention appears sufficient based on the currently available information.

### 2. requires_further_review

Use this label when:

- the use case is sufficiently described to continue review
- one or more impact, context, or control questions remain open
- the use case does not clearly fit a limited-governance profile
- the available information suggests additional analysis is needed before decision

This is the default label when the use case is reviewable but not clearly low-impact.

### 3. higher_risk_context_possible

Use this label when:

- the deployment context appears more sensitive
- the use case may materially influence decisions affecting individuals
- the affected domain or stakeholder impact suggests heightened governance attention
- the use case may require stronger controls or formal escalation
- the current reviewer cannot confidently keep the use case within a lightweight review path

This label is a governance signal, not a formal AI Act legal classification.

### 4. prohibited_use_case_concern

Use this label when:

- the described use case raises a serious concern that it may involve a type of use that should not proceed without immediate further review
- the concern is material enough that lightweight review is not appropriate
- escalation should occur before any approval-style governance outcome

This label should be used carefully and only when the concern is documented clearly.

This repository does **not** determine that a use case is legally prohibited under the EU AI Act. It only records that such a concern exists and requires escalation.

### 5. classification_unclear

Use this label when:

- the intended purpose is not clear enough
- the deployment context is too incomplete to assess
- the affected persons or likely impacts are not sufficiently understood
- the reviewer cannot produce a defensible preliminary rationale

This label should be used whenever the information base is too weak for a meaningful preliminary classification.

## Core classification factors

Reviewers should consider the following factors together.

### Intended purpose
- What is the system meant to do?
- What role does it play in a business or operational process?

### Deployment context
- Where and how will it be used?
- In what environment, function, or domain will it operate?

### Affected persons or groups
- Who may be affected directly or indirectly?
- Are there individuals or groups likely to experience meaningful impact?

### Decision influence
- Does the system inform, support, recommend, rank, prioritize, or automate decisions?
- Could its output materially shape human decisions?

### Degree of automation and human involvement
- How much human oversight exists?
- Can a human meaningfully review, intervene, or reject outputs?

### Impact sensitivity
- Could the use context create elevated concerns relating to rights, safety, fairness, transparency, or similar governance concerns?

### Uncertainty
- Are there major unknowns that limit confidence in the classification?

## Escalation rule

Escalation should be recommended when:

- the use case appears to involve a more sensitive or higher-impact context
- the potential effect on individuals appears material
- the classification rationale cannot be supported confidently at repository level
- there is concern that the use case may require legal, compliance, privacy, security, or risk review
- there is concern about a potentially prohibited type of use

Where escalation is recommended, the classification record should say so explicitly.

## Documentation rule

Every classification record should include:

- the selected preliminary governance classification
- a short rationale
- the main factors considered
- any uncertainties
- whether escalation is recommended

A classification without rationale should be treated as incomplete.

## What these rules do not do

These rules do **not**:

- assign formal legal categories under the EU AI Act
- determine compliance obligations
- replace legal interpretation
- convert NIST AI RMF into a checklist
- claim conformity with ISO/IEC 42001

## Relationship to source frameworks

### EU AI Act

These rules reflect a risk-based governance mindset and help identify when a use case may require more careful review. They do not perform formal legal classification. The AI Act itself is a legal framework that addresses AI risks through a risk-based approach.

### NIST AI RMF 1.0

These rules are compatible with context-based risk evaluation and governance review. NIST AI RMF is intended for voluntary use and should not be treated as a mandatory checklist.

### ISO/IEC 42001

These rules are compatible with a management-system approach that emphasizes documented processes, monitoring, review, and continual improvement. They do not claim conformity with ISO/IEC 42001.

## Summary

These classification rules exist to make governance classification more consistent across use cases.


They support:
- documented reasoning
- context-based review
- escalation where needed
- clear separation between governance classification and formal legal classification
