# Decision Rules

This document defines the decision rules used in the **AI Use-Case Governance Registry** repository.

Its purpose is to support consistent governance outcomes after intake, impact assessment, preliminary classification, and control review.

These rules align with concepts used in the EU AI Act, NIST AI RMF 1.0, and ISO/IEC 42001. They do **not** constitute legal advice, formal compliance determination, conformity assessment, or certification.

## Scope

These rules are used to support governance decisions for AI use cases recorded in this repository.

They are intended to help reviewers determine whether a use case should be:

- approved
- approved with conditions
- escalated
- deferred pending information
- rejected in current form

The output of these rules is a repository-level governance outcome only.

## Decision principle

### Framework requirement

The source frameworks support documented governance, accountability, risk-based review, and ongoing monitoring rather than one-time assessment only.

### Recommended practice

Governance outcomes should be based on documented inputs, recorded rationale, and clear ownership.

### Inference

For this repository, a simple rule set is sufficient as long as the outcome, rationale, and follow-up needs are recorded clearly.

## Required inputs

A governance decision should not be recorded without, at minimum:

- a use case record
- an impact assessment
- a preliminary governance classification
- a control review
- a short decision rationale
- an identified decision owner

If these inputs are missing, the appropriate outcome is normally `deferred_pending_information`.

## Decision labels

The repository uses the following governance decision labels:

- `approved`
- `approved_with_conditions`
- `requires_escalation`
- `deferred_pending_information`
- `rejected_in_current_form`

These labels are repository-level governance outcomes. They are not legal determinations.

## Rule set

### 1. approved

Use this label when all of the following are true:

- the use case is sufficiently documented
- the impact assessment is complete enough for governance review
- a preliminary governance classification has been recorded with rationale
- the relevant control areas have been reviewed
- no material blocker requiring escalation remains open
- the use case may proceed within the limits of this repository’s governance model

This label does **not** mean the use case is legally compliant, certified, or formally approved under any law or standard.

### 2. approved_with_conditions

Use this label when:

- the use case may proceed
- one or more follow-up actions are still required
- those actions do not prevent initial progression
- the required actions can be stated clearly and tracked

Typical conditions may include:

- documentation updates
- clarification of ownership
- implementation of identified controls
- completion of a follow-up review by a stated date
- confirmation of a mitigation or oversight measure

This label is appropriate when the governance position is positive but not fully closed.

### 3. requires_escalation

Use this label when:

- the use case cannot be confidently decided at repository level
- the context appears more sensitive or higher impact
- the classification suggests that stronger review may be needed
- important legal, compliance, privacy, security, or risk questions remain open
- a concern exists about a potentially prohibited or otherwise unacceptable use
- the control position is too uncertain for a lightweight governance decision

This label indicates that further review is needed before an approval-style outcome.

### 4. deferred_pending_information

Use this label when:

- material information is missing
- the use case description is incomplete
- the impact assessment is not sufficient
- the classification rationale is incomplete
- the control review is too incomplete to support decision-making

This label should be used when the problem is insufficient information rather than an adverse conclusion about the use case itself.

### 5. rejected_in_current_form

Use this label when:

- the use case should not proceed as currently described
- the identified issues are material
- the current design, use context, or control position is not acceptable within this repository’s governance model
- approval or conditional approval would be misleading

This label should be used carefully and only with clear rationale.

This repository does **not** determine legal prohibition or formal non-compliance. It records that the use case should not proceed in its current form based on the documented governance review.

## Core decision factors

Reviewers should consider the following factors together.

### Documentation sufficiency
- Is the use case described clearly enough for review?
- Are purpose, users, affected persons, and context documented?

### Impact understanding
- Have expected benefits and potential harms been identified?
- Are the affected persons or groups reasonably understood?

### Classification clarity
- Has a preliminary governance classification been recorded?
- Is the rationale documented?
- Are any major uncertainties still unresolved?

### Control position
- Have relevant control areas been reviewed?
- Are there material control gaps?
- Are any critical areas still unclear?

### Escalation need
- Is repository-level review sufficient?
- Is a more formal review likely needed?

### Follow-up needs
- Can remaining issues be handled through conditions?
- Or do they prevent a responsible decision at this stage?

## Minimum decision rule

A use case should normally be:

- `approved` only when no material blocker remains
- `approved_with_conditions` when follow-up is required but progression is still reasonable
- `requires_escalation` when repository-level review is not sufficient
- `deferred_pending_information` when the evidence base is incomplete
- `rejected_in_current_form` when the use case should not proceed as described

## Documentation rule

Every decision record should include:

- the selected decision label
- the decision date
- the decision owner
- a short rationale
- any conditions, if applicable
- whether escalation is required
- the next review date or trigger, where relevant

A decision without rationale should be treated as incomplete.

## Conditions rule

Where `approved_with_conditions` is used, the record should state:

- each condition
- the responsible owner
- the expected completion or review point
- whether unresolved conditions should trigger escalation

Conditions should be specific enough to review later.

## Escalation rule

Escalation should be recommended when:

- the use case appears to involve heightened impact or sensitivity
- the classification suggests higher-risk context may be possible
- legal, compliance, privacy, security, or risk input is needed
- there is concern about a potentially prohibited type of use
- the decision cannot be supported confidently at repository level

Where escalation is recommended, the decision should not be presented as final.

## What these rules do not do

These rules do **not**:

- assign formal legal status under the EU AI Act
- determine compliance obligations
- replace legal interpretation
- convert NIST AI RMF into a checklist
- claim conformity with ISO/IEC 42001

## Relationship to source frameworks

### EU AI Act

These rules reflect a risk-based governance mindset and support structured internal review. They do not perform legal determination under the AI Act.

### NIST AI RMF 1.0

These rules are consistent with voluntary, context-based risk management and governance review. They should not be treated as a mandatory checklist.

### ISO/IEC 42001

These rules are consistent with a documented management-system approach that includes decisions, responsibilities, review, and continual improvement. They do not claim conformity with ISO/IEC 42001.

## Summary

These decision rules exist to make governance outcomes more consistent across use cases.


They support:

- documented decision-making
- clear separation between conditions, escalation, and rejection
- traceable ownership and rationale
- a repository-level governance process that does not overstate legal certainty
