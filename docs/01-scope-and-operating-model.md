# Scope and Operating Model

## Purpose

This document defines the scope and basic operating model of the AI Use-Case Governance Registry.

The implementation is intended to show a simple, documented governance flow for enterprise AI use cases. It is designed for learning, exploration, and structured review.

It aligns at a high level with concepts used in:
- the EU AI Act,
- the NIST AI Risk Management Framework (AI RMF 1.0),
- ISO/IEC 42001.

It is not a legal determination, conformity assessment, certification artifact, or compliance claim.

---

## Scope

This implementation covers:
- registration of an AI use case,
- capture of governance-relevant information,
- progression through a simplified review flow,
- recording of governance decisions,
- tracking of monitoring and periodic review points.

The implementation focuses on governance handling at a high level.  
It is intended to provide a structured record and review path for AI use cases before and after deployment.

---

## Out of Scope

This implementation does not cover:
- formal legal classification under the EU AI Act,
- conformity assessment,
- full implementation of ISO/IEC 42001,
- production deployment,
- sector-specific regulatory analysis,
- automated compliance decisions,
- organization-specific approval structures beyond the basic roles defined below.

---

## Minimum Roles

The operating model uses the following minimum roles.

### Requester
Submits the use case for review and provides the initial information.

### Use-case owner
Owns the business use case and is responsible for the accuracy and completeness of the record.

### Reviewer
Performs the governance review based on the recorded facts, including impact, classification, and control status.

### Approver
Records the governance outcome based on the available information and review result.

### Monitoring owner
Tracks review dates, status changes, and issues after a use case has been reviewed or approved.

---

## Lifecycle Stages

The implementation uses the following stages:

1. Intake  
2. Impact assessment  
3. Preliminary risk classification  
4. Control review  
5. Governance decision  
6. Monitoring and periodic review  

These stages are used as a governance flow for the repository.  
They are not presented as a legal or certification workflow.

---

## Operating Principles

### One record per use case
Each AI use case should have one registry record that acts as the main governance record for that use case.

### Facts before decisions
Governance decisions should be based on recorded information about purpose, users, affected persons, data, deployment context, and oversight.

### Preliminary classification only
Any classification produced by the implementation is a preliminary governance classification for internal review. It is not a formal legal determination.

### Recorded decisions
Governance outcomes should be documented together with rationale, conditions where relevant, and review timing.

### Review after decision
A use case should remain subject to monitoring and periodic review after the governance decision is recorded.

---

## Relationship to Source Frameworks

### EU AI Act
The AI Act introduces a risk-based approach to the regulation of AI systems. In this implementation, that is reflected through structured intake, preliminary classification, and ongoing review.

### NIST AI RMF
NIST AI RMF 1.0 organizes AI risk management around the functions Govern, Map, Measure, and Manage, with governance acting as a cross-cutting function. In this implementation, the operating model uses those concepts at a high level to structure review and oversight.

### ISO/IEC 42001
ISO/IEC 42001 specifies requirements and guidance for establishing, implementing, maintaining, and continually improving an AI management system. In this implementation, that is reflected through documented roles, documented workflow, recorded decisions, and periodic review.

---

## Implementation Boundary

This repository is a simplified exploratory implementation.  
It is designed to show governance structure and traceability, not full organizational implementation.