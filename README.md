# AI Use-Case Governance Registry

**Status:** In progress — under active development

## Table of Contents
- [Overview](#overview)
- [Purpose](#purpose)
- [Scope](#scope)
- [Workflow](#workflow)
- [Framework Alignment](#framework-alignment)
- [Architecture](#architecture)
- [Current Status](#current-status)
- [Next Steps](#next-steps)

## Overview

This repository contains an exploratory implementation of an **AI Use-Case Governance Registry**.

It demonstrates a simple, documented process for recording and reviewing enterprise AI use cases across key governance stages, from intake to periodic review.

## Purpose

The purpose of this repository is to show how an organization can maintain a structured record of AI use cases and apply a consistent governance workflow before and after deployment.

This is a non-production implementation intended for learning, exploration, and structured design.

## Scope

This implementation focuses on the governance handling of AI use cases at a high level. It covers the registration of a use case, the capture of key governance information, progression through a simplified review flow, and the recording of governance decisions and review points.

The implementation is intentionally limited in scope and does not cover production deployment, full regulatory mapping, or organization-specific governance operating models.


## Workflow

The governance flow covered in this implementation is:

1. Intake  
2. Impact assessment  
3. Preliminary risk classification  
4. Control review  
5. Governance decision  
6. Monitoring and periodic review  

## Framework Alignment

The design is aligned with concepts used in:

- the **EU AI Act** risk-based approach
- the **NIST AI Risk Management Framework (AI RMF)**
- **ISO/IEC 42001** for AI management systems

This repository does not attempt to fully implement these frameworks. It uses selected concepts from them to shape a simple and understandable governance workflow.

## Architecture

High-level components in the implementation:

- registry for AI use-case records
- workflow stages for review and decision-making
- governance-related metadata and documentation fields
- periodic review and monitoring concept

> A simple architecture or workflow diagram will be added here.

## Current Status

Current focus areas:

- repository setup
- documentation structure
- governance workflow design
- incremental implementation of the registry

## Next Steps

Planned next steps:

- define the core data model
- implement the first workflow path
- add sample use-case records
- document architecture decisions
- expand validation and review logic
