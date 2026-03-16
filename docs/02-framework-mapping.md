# Framework Mapping

## Purpose

This document maps the implementation workflow to concepts used in the following sources:

- EU AI Act
- NIST AI Risk Management Framework (AI RMF 1.0)
- ISO/IEC 42001

This mapping is intended for governance design and documentation.
It is not a legal determination, conformity assessment, certification artifact, or compliance claim.

---

## Implementation Stages

1. Intake
2. Impact assessment
3. Preliminary risk classification
4. Control review
5. Governance decision
6. Monitoring and periodic review

---

## Mapping Table

| Implementation stage | EU AI Act | NIST AI RMF | ISO/IEC 42001 | Notes |
|---|---|---|---|---|
| Intake | Risk-based governance context | Govern, Map | Organizational context and documented processes | Records core use-case facts |
| Impact assessment | Risk-oriented review of the use case | Map, Measure | Risk and governance review within the management system | Assesses governance-relevant impact |
| Preliminary risk classification | Risk-based approach | Map, Measure, Manage | Risk treatment within the management system | Preliminary governance classification only |
| Control review | Relevant obligations depend on use case and risk | Govern, Measure, Manage | Documented controls, roles, and operational governance | Checks whether key controls are defined or evidenced |
| Governance decision | Internal response based on risk and controls | Govern, Manage | Decision, accountability, and operational follow-through | Approve / condition / escalate / reject |
| Monitoring and periodic review | Ongoing obligations where applicable | Manage, Govern | Performance evaluation and continual improvement | Tracks issues, changes, and review dates |

---

## Framework Notes

### EU AI Act

The EU AI Act uses a risk-based approach. For governance design purposes, the implementation uses that logic to support intake, preliminary classification, escalation, and ongoing review.

The implementation does not determine legal status under the AI Act. It produces a **preliminary governance classification** for internal review only.

### NIST AI RMF

NIST AI RMF 1.0 organizes AI risk management around four functions:
- Govern
- Map
- Measure
- Manage

In this implementation:
- Intake supports **Govern** and **Map**
- Impact assessment supports **Map** and **Measure**
- Control review supports **Govern**, **Measure**, and **Manage**
- Decision and monitoring support **Manage** and **Govern**

The AI RMF is voluntary and should not be treated as a prescriptive checklist.

### ISO/IEC 42001

ISO/IEC 42001 specifies requirements and provides guidance for establishing, implementing, maintaining, and continually improving an AI management system.

In this implementation, ISO/IEC 42001 is reflected through:
- documented workflow,
- assigned governance roles,
- recorded decisions,
- monitoring and periodic review.

The implementation is not a certifiable AI management system.

---

## Source Basis

- European Commission, *AI Act* overview
- European Commission, *Navigating the AI Act*
- NIST, *Artificial Intelligence Risk Management Framework (AI RMF 1.0)*
- ISO, *ISO/IEC 42001:2023 - AI management systems*