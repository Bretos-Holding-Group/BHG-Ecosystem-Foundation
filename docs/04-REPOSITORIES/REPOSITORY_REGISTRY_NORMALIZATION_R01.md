---
title: Repository Registry Normalization R01
document_id: REPOSITORY_REGISTRY_NORMALIZATION_R01
version: 1.0.0
status: Draft
document_type: Registry Normalization Record
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
  - BHG_CONSTITUTION.md
  - REPOSITORY_IDENTITY_REGISTER
  - REPOSITORY_REGISTRY
  - REPOSITORY_CLASSIFICATION
  - REPOSITORY_NAMING_STANDARD

depends_on:
  - CROSS_REPOSITORY_RECONCILIATION_R00
related_to:
  - BHG-Governance
  - BHG-Knowledge
  - ZivaLatam
  - Legalbreto
---

# Repository Registry Normalization R01

## Purpose

This record defines the controlled normalization of the legacy Repository Registry model against the current institutional identity model.

It is an amendment record, not a replacement authority source. Until incorporated into the canonical Registry, the existing Registry remains historically preserved while the clauses identified below are treated as normalization targets.

## Canonical Institutional States

The registry model shall distinguish at minimum:

- `BHG-CORE` — repository institutionally recognized as part of the BHG core;
- `INDEPENDENT` — repository or project not institutionally part of BHG;
- `INDEPENDENT / FUTURE-INTEGRATION-CANDIDATE` — independent today, with documented conditional future integration intent;
- `PLANNED` — future repository concept not yet materialized;
- `INTEGRATED` — formally integrated through an approved institutional process.

## Repository Hosting Boundary

GitHub organization placement does not determine institutional affiliation.

The following do not independently establish BHG membership:

- repository hosting location;
- shared standards;
- shared tooling;
- shared documentation methods;
- strategic intent;
- future integration intent.

Institutional affiliation requires explicit recognition through the applicable governance process.

## Current Classification Baseline

| Repository | State | Canonical identity | Registry disposition |
|---|---|---|---|
| BHG-Governance | BHG-CORE | BHG Governance | Preserve |
| BHG-Ecosystem-Foundation | BHG-CORE | BHG Ecosystem Foundation | Preserve |
| bhg-knowledge | BHG-CORE | BHG Knowledge | Rename candidate; impact analysis required |
| ZivaLatam | INDEPENDENT / FUTURE-INTEGRATION-CANDIDATE | ZivaLatam | Preserve independent identity |
| Legalbreto | INDEPENDENT | Legalbreto | Exclude from BHG institutional normalization |
| — | PLANNED | BHG Legal Framework | Do not infer from Legalbreto |

## Ownership Language Normalization

The legacy registry schema uses `legal_owner` and includes examples that imply an existing BHG legal entity.

Until a constitutive legal record establishes a BHG legal entity and applicable ownership, present-tense legal ownership shall not be inferred from repository governance records.

Institutional ownership, governance responsibility, and technical maintenance must remain distinct fields.

## Recognition Rule

A repository may be technically accessible, operationally useful, or strategically relevant without being an official BHG institutional asset.

Official recognition requires the applicable identity, purpose, classification, authority, lifecycle, and governance records.

## Historical Preservation

This normalization does not delete or rewrite historical repository records. Historical names, previous classifications, and prior assumptions remain traceable as historical artifacts.

## Required Canonical Registry Update

The next Registry implementation change shall:

1. replace ambiguous membership language with the state model above;
2. distinguish BHG Core from independent and future-integration candidates;
3. qualify all prospective legal ownership references;
4. preserve `Legalbreto` as independent;
5. preserve `ZivaLatam` as independent with conditional future-integration intent;
6. maintain `BHG Legal Framework` as planned and distinct from `Legalbreto`;
7. record repository name history separately from institutional identity.

## Authority Boundary

This record does not create ownership, legal personality, subsidiary status, or integration. It does not authorize a repository rename.

Human governance remains responsible for institutional decisions.

## Disposition

**R01 — NORMALIZATION READY FOR CANONICAL REGISTRY INCORPORATION.**
