# Decision Model

## Purpose

This document defines the decision model used in the **AI Use-Case Governance Registry** repository.

Its purpose is to make governance outcomes explicit, documented, and traceable after intake, impact assessment, preliminary classification, and control review.

This document aligns with concepts used in the EU AI Act, NIST AI RMF 1.0, and ISO/IEC 42001. It does **not** constitute legal advice, formal compliance determination, conformity assessment, or certification.

## Scope

The decision model applies to the internal governance outcome recorded for each AI use case included in this repository.

It is intended to answer:

- whether the use case is sufficiently understood for governance review
- whether the available documentation is sufficient
- whether additional controls or escalation are needed
- whether the use case may proceed in its current form from a governance perspective

## Nature of the decision

### Framework requirement

The source frameworks support documented governance, accountability, review, and risk-based decision-making.

### Recommended practice

A governance repository should make decision outcomes and their rationale explicit.


## Decision inputs

A governance decision should be based on the following inputs:

1. use case registration record
2. impact assessment
3. preliminary risk classification
4. control review
5. reviewer notes and identified gaps

A decision should not be recorded without documented inputs.

## Decision states

This repository uses the following decision states.

### 1. Approved

Use this state when:

- the use case is sufficiently described
- the main impacts have been documented
- the preliminary classification has been recorded
- the relevant controls have been reviewed
- no unresolved issue requires escalation before proceeding

This does **not** mean the use case is legally compliant or certified. It means the use case may proceed within the scope of this repository’s governance model.

### 2. Approved with conditions

Use this state when:

- the use case may proceed
- one or more follow-up actions are required
- those actions do not prevent initial progression
- the conditions can be tracked and reviewed

Examples of conditions may include:
- additional documentation
- clarification of ownership
- implementation of identified controls
- defined review date before wider deployment

This is a governance outcome, not a legal determination.

### 3. Requires escalation

Use this state when:

- the use case cannot be adequately reviewed at the current level
- the impact or classification is unclear
- the use case appears likely to require more formal review
- legal, compliance, privacy, security, or risk input is needed
- the control position cannot be determined confidently

This state indicates that lightweight review is not sufficient.

### 4. Deferred pending information

Use this state when:

- the use case description is incomplete
- material information is missing
- the assessment cannot be completed on the available evidence
- a decision would be premature

This state is appropriate when the issue is lack of information, rather than a negative decision on the use case itself.

### 5. Rejected in current form

Use this state when:

- the use case should not proceed as currently described
- the identified issues are material
- the current design or governance basis is insufficient
- a substantial redesign or re-submission would be required

This state should be used carefully and with documented rationale.

## Decision criteria

The decision should consider the following questions:

### Documentation sufficiency
- Is the use case described clearly enough for review?
- Are the purpose, users, affected stakeholders, and deployment context documented?

### Impact understanding
- Have the likely benefits and potential harms been identified?
- Are affected persons or groups understood at a reasonable level?

### Preliminary classification clarity
- Has a preliminary governance classification been recorded?
- Is the rationale documented?
- Are there unresolved classification uncertainties?

### Control position
- Have relevant controls been reviewed?
- Are any essential controls missing, unclear, or deferred?

### Need for escalation
- Does the use case require review beyond this repository-level governance model?

## Minimum decision rule

A decision should only be recorded when all of the following are true:

- the use case record exists
- the impact assessment exists
- a preliminary classification exists
- the control review exists
- the rationale for the decision is documented
- the decision owner is identified
- a review date or trigger is recorded where relevant

If these conditions are not met, the appropriate outcome is normally **Deferred pending information** or **Requires escalation**.

## Decision record

Each decision should record:

- use case identifier
- decision state
- date
- decision owner
- summary rationale
- conditions, if any
- escalation note, if any
- next review date or trigger

This repository may represent that information inside the use case record or in a dedicated decision artifact, depending on implementation simplicity.

## Escalation guidance

Escalation should be considered when one or more of the following applies:

- the intended use is ambiguous
- the affected domain or stakeholder impact is unclear
- the use case may fall into a higher-risk context
- accountability is unclear
- required controls cannot be identified confidently
- important review functions are outside the scope of this repository

This repository does not define formal organizational escalation paths. It only indicates when further governance review is appropriate.

## What this decision model does not do

This decision model does **not**:

- make a formal legal classification under the EU AI Act
- determine conformity with the AI Act
- certify alignment with ISO/IEC 42001
- implement NIST AI RMF as a checklist
- replace legal, compliance, privacy, security, or audit review

## Relationship to source frameworks

### EU AI Act

This decision model reflects a risk-based governance mindset. Any classification or decision in this repository remains preliminary and internal to the repository’s governance design.

### NIST AI RMF 1.0

This decision model is consistent with governance and risk response thinking across GOVERN, MAP, MEASURE, and MANAGE. It should not be interpreted as a mandatory sequence or checklist.

### ISO/IEC 42001

This decision model is consistent with documented governance, accountability, control consideration, monitoring, and continual review within an AI management system context.

## Summary

The purpose of this decision model is to ensure that each AI use case reaches a documented governance outcome based on recorded review inputs.


The decision states used in this repository are:

- Approved
- Approved with conditions
- Requires escalation
- Deferred pending information
- Rejected in current form
