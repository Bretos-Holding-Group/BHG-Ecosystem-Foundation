---
title: Repository Identity Reconciliation
document_id: REPOSITORY_IDENTITY_RECONCILIATION
version: 0.1.0
status: Draft
document_type: Repository Identity Reconciliation Record
governance_level: Foundation
owner: BHG Ecosystem Foundation
approval_authority: BHG Governance Council
classification: Internal
language: en
repository: BHG-Ecosystem-Foundation

governed_by:
  - BHG_CONSTITUTION.md
  - REPOSITORY_REGISTRY.md
  - REPOSITORY_NAMING_STANDARD.md
  - REPOSITORY_CLASSIFICATION.md

depends_on:
  - REPOSITORY_REGISTRY.md
  - REPOSITORY_NAMING_STANDARD.md
  - REPOSITORY_CLASSIFICATION.md

related_to:
  - REPOSITORY_LIFECYCLE.md
  - REPOSITORY_DEPENDENCY_MODEL.md
---

# Repository Identity Reconciliation

## Purpose

This document establishes a controlled reconciliation layer between the repositories that currently exist in the BHG GitHub account and their institutional identities.

It is a normalization record, not an authorization to rename repositories.

The purpose is to distinguish:

- current technical repository name;
- proposed canonical institutional name;
- repository classification;
- identity status;
- rename requirement;
- evidence required before any rename.

No repository rename is authorized by this document.

## Current GitHub Inventory

The GitHub installation currently exposes the following repositories under `Bretos-Holding-Group`:

| Current repository name | Current identity status | Preliminary institutional classification | Proposed canonical name | Rename decision |
|---|---|---|---|---|
| `BHG-Governance` | Existing | Governance Repository | `BHG-Governance` | Retain |
| `BHG-Ecosystem-Foundation` | Existing | Foundation Repository | `BHG-Ecosystem-Foundation` | Retain |
| `bhg-knowledge` | Existing | Knowledge Repository | `BHG-Knowledge` | Evaluate rename |
| `ZivaLatam` | Existing | Product / Engineering Repository | `ZivaLatam` | Retain pending entity naming reconciliation |
| `Legalbreto` | Existing | Unresolved; requires scope verification | Pending | Do not rename |

The inventory above records observed technical existence only. Presence in the GitHub account does not by itself establish institutional authority, ownership, classification, or canonical recognition.

## Canonical Identity Rules

1. A GitHub repository name and an institutional repository identity are related but distinct concepts.
2. The Repository Registry is the institutional record for recognized repositories.
3. A rename shall never be performed solely to satisfy a naming pattern.
4. Existing names with established product or entity identity may remain valid when classification and governance justify the exception.
5. A proposed canonical name must be validated against purpose, classification, dependencies, references, external identity, and historical continuity.
6. Historical names shall be preserved when a rename is approved.
7. No rename shall occur before an impact assessment and explicit governance approval.

## Initial Reconciliation Findings

### `BHG-Governance`

The current name conforms to the established governance naming pattern and clearly identifies the repository's role.

**Decision:** retain.

### `BHG-Ecosystem-Foundation`

The current name conforms to the ecosystem/foundation naming pattern and is already used consistently by the repository itself.

**Decision:** retain.

### `bhg-knowledge`

The repository's internal identity is already documented as **BHG-Knowledge**, while the GitHub technical name remains lowercase `bhg-knowledge`.

This is a direct identity/naming mismatch and should be evaluated for normalization.

**Decision:** propose `BHG-Knowledge`; do not rename until impact analysis and governance approval are complete.

### `ZivaLatam`

The repository identifies itself as **Ziva Latam** and contains the Ziva Engineering System. Its identity is product/entity-oriented rather than a generic BHG infrastructure repository.

The current repository naming standard permits product-oriented names, but the relationship between BHG institutional naming and Ziva entity naming requires explicit classification before any rename is considered.

**Decision:** retain provisionally; reconcile through the BHG entity/product identity model rather than applying the BHG infrastructure prefix mechanically.

### `Legalbreto`

The repository exists in the BHG GitHub account but its repository-level purpose could not be established from a README at the time of this reconciliation.

Its name alone is insufficient evidence for classification or canonical institutional recognition.

**Decision:** do not rename or classify conclusively until repository scope, purpose, ownership, and relationship to the BHG Legal domain are verified.

## Rename Gate

No repository rename may proceed until all of the following are available:

- confirmed repository purpose;
- confirmed institutional classification;
- confirmed canonical identity;
- dependency and reference impact assessment;
- external integration assessment;
- historical identity record;
- governance approval;
- implementation and post-rename verification plan.

## Normalization Sequence

The recommended sequence is:

Current Inventory
    ↓
Identity Reconciliation
    ↓
Purpose and Classification Verification
    ↓
Canonical Name Proposal
    ↓
Reference / Dependency Impact Analysis
    ↓
Governance Review
    ↓
Rename Decision
    ↓
Controlled Rename (if approved)
    ↓
Reference Update
    ↓
Post-Rename Verification
    ↓
Registry Finalization

## Non-Authority Clause

This document does not:

- rename repositories;
- create repository authority;
- establish legal ownership;
- override BHG Governance;
- establish a new repository classification by itself;
- authorize implementation changes in operational repositories.

It exists to provide a controlled evidence layer for the repository identity normalization process.
