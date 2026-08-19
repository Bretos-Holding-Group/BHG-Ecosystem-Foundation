---
title: Repository Identity Reconciliation
document_id: REPOSITORY_IDENTITY_RECONCILIATION
version: 0.2.0
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

This document establishes a controlled reconciliation layer between the repositories currently visible through the BHG GitHub account and their institutional identities, affiliations, and scope.

It is a normalization record, not an authorization to rename repositories or establish institutional affiliation.

The purpose is to distinguish:

- current technical repository name;
- canonical institutional identity, where recognized;
- repository classification;
- current institutional relationship;
- future integration intent, where applicable;
- rename requirement;
- evidence required before any rename or integration decision.

No repository rename, ownership transfer, subsidiary relationship, or institutional integration is authorized by this document.

## Institutional Affiliation Rules

1. Presence within the `Bretos-Holding-Group` GitHub account does not by itself establish institutional affiliation, ownership, governance authority, or subsidiary status.
2. Repository hosting location, shared standards, shared tooling, branding, or future strategic intent do not independently establish BHG membership.
3. Institutional recognition must be established through the applicable BHG governance and registry process.
4. A repository may be architecturally aligned with BHG while remaining institutionally independent.
5. Future integration intent does not establish present legal ownership, control, governance, or subsidiary status.
6. An independently operated entity may maintain its own policies and operational governance while designing for compatibility with future BHG governance.
7. Any future institutional integration must be separately approved, documented, and verified before the relationship is treated as effective.

## Current GitHub Inventory

The GitHub installation currently exposes the following repositories under `Bretos-Holding-Group`:

| Current repository name | Current identity / scope | Institutional classification | Current relationship to BHG | Proposed canonical name | Rename / integration status |
|---|---|---|---|---|---|
| `BHG-Governance` | BHG Governance | BHG Core — Governance | Institutional Core | `BHG-Governance` | Retain |
| `BHG-Ecosystem-Foundation` | BHG Ecosystem Foundation | BHG Core — Foundation | Institutional Core | `BHG-Ecosystem-Foundation` | Retain |
| `bhg-knowledge` | BHG-Knowledge | BHG Core — Knowledge | Institutional Core | `BHG-Knowledge` | Evaluate rename |
| `ZivaLatam` | Ziva Latam / Ziva operational system | Independent Operational Entity / Future BHG Subsidiary Candidate | Independent today; BHG-aligned by design; future integration intent | `ZivaLatam` | Retain; entity/integration reconciliation required |
| `Legalbreto` | Independent migration-case traceability project | Independent Project — Out of BHG Scope | Independent; no current institutional affiliation | `Legalbreto` | Retain; exclude from BHG core |

The inventory records technical existence separately from institutional status. `Legalbreto` is hosted under the BHG GitHub account for operational convenience but is not a BHG repository. ZivaLatam is also currently independent and is not a BHG subsidiary; its future integration is an explicit strategic possibility, not a present legal or institutional relationship.

## BHG Core

For the current normalization exercise, the BHG institutional core consists of:

- `BHG-Governance`;
- `BHG-Ecosystem-Foundation`;
- `bhg-knowledge`, whose canonical institutional identity is **BHG-Knowledge** pending controlled technical rename.

These repositories form the current documentation and governance nucleus. Their recognition does not depend on the future legal incorporation of BHG; however, nothing in this document creates legal personality or legal ownership where it does not yet exist.

## Future Integration Model

An independent entity may be designed to remain compatible with BHG governance before any formal integration occurs.

The canonical lifecycle is:

`INDEPENDENT` → `FUTURE-INTEGRATION-CANDIDATE` → `INTEGRATED`

These states are mutually meaningful and must not be conflated.

### ZivaLatam

ZivaLatam is currently an independent operational entity/product and must retain its own identity and operational rules.

It is intentionally designed to remain aligned with BHG architectural and governance principles so that a future integration can occur without requiring a fundamental reconstruction of its systems.

Its current state is:

**INDEPENDENT / FUTURE-INTEGRATION-CANDIDATE**

This status does not establish present BHG ownership, control, subsidiary status, or legal subordination.

BHG may maintain a record of the strategic future-integration intent, while ZivaLatam should maintain its own corresponding record of alignment and future integration intent. Neither record, by itself, creates the future relationship.

### Legalbreto

Legalbreto is a separate project created for migration-case traceability, evidence management, and preservation of case-related records.

It is currently and intentionally outside the BHG institutional scope. It may use compatible engineering and documentation standards without becoming a BHG system.

Its current state is:

**INDEPENDENT**

Any future integration would require a new, explicit institutional decision and onboarding process. No future integration intent is assumed by this reconciliation record.

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

It should therefore retain its own name and identity rather than receive a mechanical `BHG-` prefix. Its future integration intent should be documented separately by BHG and by ZivaLatam without implying present institutional control.

**Decision:** retain; perform entity/integration reconciliation separately.

### `Legalbreto`

The repository is an independent migration-case traceability project. Its presence under the BHG GitHub account is an operational hosting arrangement and does not constitute BHG affiliation.

Its purpose and independence are now explicitly established for this normalization scope.

**Decision:** retain as `Legalbreto`; exclude from BHG Core, BHG governance authority, and BHG repository normalization unless a future formal integration decision is made.

## Naming Rules

1. Core BHG repositories should use the established `BHG-*` naming convention where the repository represents a BHG institutional capability.
2. Independent entities, products, and projects may retain their own canonical names when those names represent their actual identity.
3. A BHG prefix must not be applied solely to make names visually uniform.
4. Naming must follow institutional classification rather than the reverse.
5. A repository rename must preserve historical identity and references.
6. A technical rename must not be interpreted as creating or changing legal ownership.

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

## Integration Gate

No future BHG integration may be treated as effective until all applicable conditions are satisfied:

- independent status and current ownership are documented;
- strategic intent is documented by both sides where applicable;
- legal and organizational implications are assessed;
- governance approval is obtained;
- integration terms and authority boundaries are documented;
- technical and documentary dependencies are assessed;
- the integrated entity is entered into the applicable institutional registry;
- post-integration verification is completed.

## Normalization Sequence

The recommended sequence is:

Current Inventory
    ↓
Identity Reconciliation
    ↓
Purpose and Classification Verification
    ↓
Institutional Relationship Classification
    ↓
Canonical Name Proposal
    ↓
Reference / Dependency Impact Analysis
    ↓
Governance Review
    ↓
Rename or Integration Decision
    ↓
Controlled Implementation (if approved)
    ↓
Reference Update
    ↓
Post-Change Verification
    ↓
Registry Finalization

## Non-Authority Clause

This document does not:

- rename repositories;
- create repository authority;
- establish legal ownership;
- establish a subsidiary relationship;
- override BHG Governance;
- convert strategic intent into present institutional affiliation;
- establish a new repository classification by itself;
- authorize implementation changes in operational repositories.

It exists to provide a controlled evidence layer for repository identity, institutional boundary, naming, and future integration normalization.
