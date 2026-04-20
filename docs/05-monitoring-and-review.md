# Monitoring and Review

## Purpose

This document defines how the **AI Use-Case Governance Registry** repository handles monitoring, review, and reassessment after an initial governance decision.

Its purpose is to ensure that governance does not stop at intake and decision, and that material changes, emerging issues, and scheduled reviews can be recorded in a simple and traceable way.

This document aligns with concepts used in the EU AI Act, NIST AI RMF 1.0, and ISO/IEC 42001. It does **not** constitute legal advice, formal compliance determination, conformity assessment, or certification.

## Scope

This document applies to AI use cases that have already passed through:

1. intake
2. impact assessment
3. preliminary risk classification
4. control review
5. governance decision

It defines when a use case should be reviewed again and what types of change or issue should trigger follow-up governance attention.

## Why monitoring and review matter

### Framework requirement

The source frameworks support ongoing governance, monitoring, review, and adaptation over time rather than one-time assessment only.

### Recommended practice

A governance repository should record review triggers and follow-up expectations after an initial decision.

### Inference

For this repository, a lightweight monitoring and review model is sufficient as long as review triggers, change events, and review dates are documented clearly.

## Monitoring objective

The objective of monitoring and review in this repository is to determine whether the original governance basis still holds.

This includes checking whether:

- the intended purpose remains unchanged
- the deployment context remains unchanged
- the stakeholder impact remains materially similar
- the preliminary classification still appears appropriate
- previously identified controls remain suitable
- new issues or incidents require follow-up
- escalation is now needed

## Review triggers

A use case should be reviewed again when one or more of the following occurs.

### 1. Material change in intended use

Review should be triggered when the use case changes in a way that affects its purpose, outputs, users, affected stakeholders, or decision influence.

### 2. Material change in deployment context

Review should be triggered when the use case is introduced into a new environment, business function, geography, or decision context.

### 3. Material change in data

Review should be triggered when there is a significant change in:

- data sources
- data categories
- data sensitivity
- downstream data use

### 4. Material change in model or provider

Review should be triggered when the model, service provider, deployment architecture, or system dependency changes in a way that may affect governance assumptions.

### 5. Incident, complaint, or control failure

Review should be triggered when there is evidence that:

- an identified control is not working as expected
- an issue has occurred affecting users or other stakeholders
- a complaint or concern raises questions about impact, transparency, or oversight

### 6. Scheduled periodic review

Review should also occur at a planned interval, even if no major issue has been reported.

This repository does not prescribe a universal review period. The review date should be recorded based on the context of the use case.

## Review questions

A follow-up review should consider the following questions:

### Governance basis
- Does the original use case description still reflect the system in use?
- Does the existing documentation remain current?

### Impact
- Have benefits, risks, or affected stakeholders changed?
- Have any new harms or concerns emerged?

### Preliminary classification
- Does the current use case still appear to fit the previously recorded preliminary governance classification?
- Is escalation now needed?

### Controls
- Are the identified controls still appropriate?
- Have any required controls not been implemented or maintained?

### Decision status
- Should the previous governance decision remain in place?
- Should the decision be updated, conditioned again, deferred, escalated, or reconsidered?

## Monitoring record

For each review event, the repository should record at minimum:

- use case identifier
- review date
- review trigger
- summary of change or issue
- reviewer
- outcome
- follow-up actions, if any
- next review date or trigger

This may be represented within the use case record or in a separate review log, depending on implementation simplicity.

## Possible review outcomes

A monitoring or review event may result in one or more of the following outcomes:

- no material change identified
- documentation update required
- impact assessment update required
- classification review required
- control review update required
- governance decision update required
- escalation required

These are repository-level governance outcomes only. They are not legal determinations.

## Relationship to decision-making

Monitoring and review do not replace the original governance decision model. They support re-entry into the governance flow when circumstances change.

Where a material change is identified, the use case may need to return to one or more earlier stages, including:

- impact assessment
- preliminary risk classification
- control review
- governance decision

## Design limitations

This repository uses a simple monitoring and review model.

It does **not**:

- provide automated monitoring
- define operational metrics or testing methods in detail
- create a formal incident management framework
- determine legal obligations under the EU AI Act
- certify alignment with ISO/IEC 42001
- implement NIST AI RMF as a checklist

## Relationship to source frameworks

### EU AI Act

This document reflects the need for governance attention across the lifecycle of relevant AI uses. In this repository, any reassessment remains a preliminary governance activity and not a formal legal classification process.

### NIST AI RMF 1.0

This document is consistent with the idea that AI risk management is ongoing, context-dependent, and voluntary rather than a one-time checklist exercise.

### ISO/IEC 42001

This document is consistent with a management-system approach that includes monitoring, review, and continual improvement.

## Summary

The monitoring and review model in this repository exists to ensure that governance remains traceable after an initial decision.

It focuses on:

- material change
- issue-triggered review
- scheduled periodic review
- documented follow-up
- re-entry into governance review when needed
