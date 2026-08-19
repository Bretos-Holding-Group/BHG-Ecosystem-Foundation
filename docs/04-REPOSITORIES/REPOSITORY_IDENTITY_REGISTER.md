---
title: Repository Identity Register
document_id: REPOSITORY_IDENTITY_REGISTER
version: 0.1.0
status: Draft
document_type: Repository Identity Register
governance_level: Foundation
owner: BHG Ecosystem Foundation
approval_authority: BHG Governance Council
created: 2026-08-19
last_updated: 2026-08-19
effective_date: null
classification: Internal
language: en
repository: BHG-Ecosystem-Foundation

governed_by:
  - REPOSITORY_REGISTRY
  - REPOSITORY_CLASSIFICATION
  - REPOSITORY_DEPENDENCY_MODEL

depends_on:
  - ARCHITECTURE_MAP
  - REPOSITORY_REGISTRY
  - REPOSITORY_CLASSIFICATION

related_to:
  - REPOSITORY_NAMING_STANDARD
  - SOURCE_OF_TRUTH_MODEL
  - CROSS_REPOSITORY_MODEL
---

# Repository Identity Register

## Purpose

This register establishes the current institutional classification and identity boundary of repositories relevant to the BHG ecosystem.

It distinguishes institutional membership, operational independence, future integration intent, technical hosting, and planned repositories.

A GitHub organization or hosting location does not by itself establish institutional affiliation.

## Identity States

Repositories and repository candidates shall use the following institutional states where applicable:

- `BHG-CORE` — officially recognized as part of the BHG institutional core.
- `INDEPENDENT` — currently outside BHG institutional membership.
- `INDEPENDENT / FUTURE-INTEGRATION-CANDIDATE` — independent today, with a documented possibility of future BHG integration.
- `PLANNED` — intended repository not yet materially created or institutionally recognized.
- `INTEGRATED` — formally integrated into BHG through the applicable institutional and legal process.

These states describe institutional relationship. They do not replace repository lifecycle states.

## Current Register

| Technical Repository | Canonical Institutional Identity | Classification | Current State | BHG Membership | Future Integration | Notes |
|---|---|---|---|---|---|---|
| `BHG-Governance` | BHG Governance | Governance Repository | BHG-CORE | Yes | N/A | Institutional governance domain |
| `BHG-Ecosystem-Foundation` | BHG Ecosystem Foundation | Foundation Repository | BHG-CORE | Yes | N/A | Institutional and ecosystem architecture |
| `bhg-knowledge` | BHG Knowledge | Knowledge Repository | BHG-CORE | Yes | N/A | Technical repository name remains pending normalization |
| `ZivaLatam` | ZivaLatam | Product / Operational Entity | INDEPENDENT / FUTURE-INTEGRATION-CANDIDATE | No | Yes | Independent today; designed for future compatibility |
| `Legalbreto` | Legalbreto | Independent Project | INDEPENDENT | No | No current intent | Outside BHG scope; maintained separately for an independent project |
| — | BHG Legal Framework | Legal Repository | PLANNED | Planned | N/A | Future BHG repository; must not be inferred from `Legalbreto` |

## Institutional Boundary Rules

### Rule 1 — Hosting Does Not Establish Membership

A repository hosted under the BHG GitHub organization is not automatically a BHG institutional repository.

### Rule 2 — Shared Standards Do Not Establish Membership

Use of BHG-compatible architecture, documentation, tooling, or standards does not by itself establish institutional affiliation.

### Rule 3 — Strategic Intent Does Not Establish Membership

A documented future integration intent does not create present ownership, control, subsidiary status, legal subordination, or governance authority.

### Rule 4 — Formal Integration Is Required

A repository or entity may transition to `INTEGRATED` only after the applicable institutional, governance, and legal integration process has been completed and recorded.

### Rule 5 — Independent Projects Remain Independent

An independent project may use BHG-compatible methods without becoming subject to BHG governance.

### Rule 6 — Planned Repositories Are Distinct From Independent Repositories

A planned BHG repository is an intended future institutional component. An independent repository is outside the BHG institutional scope. Neither state shall be inferred from hosting location alone.

## ZivaLatam Boundary

ZivaLatam is currently:

`INDEPENDENT / FUTURE-INTEGRATION-CANDIDATE`

BHG maintains its future integration intent record from the BHG perspective, while ZivaLatam maintains its independent counterpart.

Neither record creates a present subsidiary relationship.

If integration is formally completed in the future, the identity state may transition to `INTEGRATED` only after the applicable integration gate is satisfied.

## Legalbreto Boundary

`Legalbreto` is an independent project and is outside the current BHG institutional scope.

Its presence under the BHG GitHub organization is an operational hosting arrangement and does not establish BHG membership.

`Legalbreto` must not be reclassified as `BHG-Legal-Framework` or any other BHG repository without a separate institutional decision and integration process.

## Naming Boundary

Institutional repository naming shall be governed by the applicable BHG naming standard.

Canonical institutional identity and technical repository name are separate fields and must not be conflated.

A repository rename shall require impact analysis, reference reconciliation, approval, and post-change verification.

## Change Control

Changes to this register affecting identity, classification, membership, integration state, ownership, or canonical naming require:

1. explicit change proposal;
2. impact evaluation;
3. applicable governance review;
4. approval before institutional recognition;
5. historical traceability;
6. post-change verification.

## Non-Authority Clause

This Draft register does not create ownership, legal personality, subsidiary status, governance authority, or integration by itself.

It records the current identity model and provides the controlled baseline for subsequent repository normalization.
