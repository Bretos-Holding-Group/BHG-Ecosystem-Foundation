---
title: BHG Knowledge Reference Inventory R01
document_id: BHG_KNOWLEDGE_REFERENCE_INVENTORY_R01
version: 1.0.0
status: Draft
document_type: Repository Reference Inventory
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
  - REPOSITORY_IDENTITY_REGISTER
  - REPOSITORY_REGISTRY
  - REPOSITORY_NAMING_STANDARD
  - CROSS_REPOSITORY_RECONCILIATION_R00
  - REPOSITORY_REGISTRY_NORMALIZATION_R01
  - REPOSITORY_NAMING_SCOPE_NORMALIZATION_R01
related_to:
  - BHG-Governance
  - bhg-knowledge
  - ZivaLatam
  - Legalbreto
---

# BHG Knowledge Reference Inventory R01

## Purpose

Establish the pre-rename reference inventory for the technical repository name `bhg-knowledge` and distinguish references that must change from references that must remain historical.

## Search Scope

The inventory was executed against the current accessible repository state after Repository Registry and Naming Scope normalization.

The exact technical string `bhg-knowledge` was searched across:

- `BHG-Governance`
- `BHG-Ecosystem-Foundation`
- `bhg-knowledge`
- `ZivaLatam`

The current indexed results identified the principal active and historical references below. GitHub code search is an indexed control, not a proof of absence from every generated, external, cached, or local artifact; therefore a final post-rename verification remains mandatory.

## Reference Classification

### Active / Reconciliation Required

The following BHG-Governance artifacts contain the current technical repository name and must be reconciled before rename execution:

| Path | Class | Required action |
|---|---|---|
| `ARCHITECTURE_MAP.md` | ACTIVE | Update target reference to canonical repository identity/name after rename gate |
| `docs/00-GOVERNANCE/BHG_REPOSITORY_AUTHORITY_SEQUENCE.md` | ACTIVE | Reconcile repository identifier and authority reference |
| `docs/02-STANDARDS/NAMING_STANDARD.md` | ACTIVE | Align technical-name reference with canonical naming model |
| `docs/06-AUDIT/NORMATIVE_CONFLICT_REGISTER.md` | ACTIVE/HISTORICAL | Update active reference while preserving historical context |
| `docs/00-GOVERNANCE/CANONICAL_AUTHORITY_MODEL.md` | ACTIVE | Verify whether repository identifier is normative and update if required |

### Automation / Verification Required

The following artifacts require validation before and after rename:

| Path | Class | Required action |
|---|---|---|
| `.github/workflows/canonical-core-score-r00.yml` | AUTOMATION | Verify repository target/reference; rerun after rename |
| `tools/canonical_core_score_r00.py` | AUTOMATION | Verify repository identifier/reference; test after rename |
| `artifacts/canonical-core-score-r00.json` | HISTORICAL GENERATED | Preserve provenance; regenerate only where workflow requires current-state output |

### Historical Evidence

The following artifacts contain historical discovery or audit references and must not be rewritten merely to erase the former technical name:

| Path | Class | Required action |
|---|---|---|
| `audit/canonical-core-discovery-r00.md` | HISTORICAL | Preserve original reference and provenance |
| `audit/canonical-core-candidate-register-r00.md` | HISTORICAL | Preserve original reference and provenance |
| `docs/00-GOVERNANCE/BHG_GOVERNANCE_CORE_NORMALIZATION_N0_BASELINE_V0_1.md` | HISTORICAL/BASELINE | Preserve baseline identity; update only if the document explicitly requires an active pointer |

## Canonical Identity Rule

The institutional identity is **BHG Knowledge**. The current technical repository name is `bhg-knowledge`. The proposed technical target is `BHG-Knowledge`.

The rename must not alter historical evidence, document provenance, commit history, or the fact that `bhg-knowledge` was the former technical identifier.

## External and Independent Boundary

No evidence from the current inventory authorizes reclassification of `ZivaLatam` or `Legalbreto` as BHG repositories. Their independent identities remain unaffected by the proposed `bhg-knowledge` rename.

## Pre-Rename Gate

Before execution, the following must be true:

1. every active reference has a disposition;
2. automation references have been validated;
3. historical artifacts are explicitly protected;
4. external integrations and repository URLs have been assessed;
5. the old and target names are recorded in the canonical registry;
6. governance approval authorizes the rename;
7. a post-rename repository-wide verification plan exists.

## Disposition

**R01 — REFERENCE INVENTORY ESTABLISHED; RENAME NOT YET AUTHORIZED.**

This record establishes evidence for the next rename-impact decision. It does not itself authorize repository rename or mass reference rewriting.
