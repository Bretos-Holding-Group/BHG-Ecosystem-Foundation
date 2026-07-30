---
title: Architecture Map
document_id: ARCHITECTURE_MAP
version: 1.0.0
status: Draft
document_type: Repository Architecture Map
governance_level: Foundation
owner: BHG Ecosystem Foundation
approval_authority: BHG Governance Council
created: 2026-07-29
last_updated: 2026-07-29
effective_date: TBD
classification: Internal
language: en
repository: BHG-Ecosystem-Foundation

governed_by:
  - docs/00-FOUNDATION/FOUNDATION_PRINCIPLES.md
  - docs/00-FOUNDATION/FOUNDATION_PHILOSOPHY.md
  - docs/02-ECOSYSTEM/ECOSYSTEM_ARCHITECTURE.md
  - docs/02-ECOSYSTEM/ECOSYSTEM_LAYERS.md

governs:
  - Repository Structure
  - Domain Structure
  - Architecture Map Interpretation
  - Repository Boundary Definitions

depends_on:
  - docs/00-FOUNDATION/FOUNDATION_PRINCIPLES.md
  - docs/02-ECOSYSTEM/ECOSYSTEM_ARCHITECTURE.md
  - docs/02-ECOSYSTEM/ECOSYSTEM_LAYERS.md

related_to:
  - README.md
  - docs/04-REPOSITORIES/REPOSITORY_REGISTRY.md
  - docs/04-REPOSITORIES/REPOSITORY_CLASSIFICATION.md
  - docs/04-REPOSITORIES/REPOSITORY_DEPENDENCY_MODEL.md
  - docs/06-EVOLUTION/FOUNDATION_NORMALIZATION_ROADMAP.md
---

# Architecture Map

> Official repository architecture map for the BHG Ecosystem Foundation repository.

---

# Purpose

The Architecture Map defines the official structural organization of the BHG-Ecosystem-Foundation repository.

It establishes:

- repository scope;
- domain hierarchy;
- materialized domains;
- planned domains;
- dependency direction;
- repository boundaries;
- architecture interpretation rules.

The Architecture Map is an architectural reference.

It does not replace governance, legal authority or source-of-truth ownership.

---

# Repository Identity

The repository represented by this Architecture Map is:

BHG-Ecosystem-Foundation

Its purpose is to define, preserve and evolve the institutional architecture of the broader BHG ecosystem.

This repository is not the operational governance repository, legal repository, knowledge repository or product repository.

Those responsibilities belong to their respective ecosystem components.

---

# Repository Architectural Scope

The repository currently contains the following materialized domains:

00-FOUNDATION
01-IDENTITY
02-ECOSYSTEM
03-ORGANIZATION
04-REPOSITORIES
05-INTEGRATION
06-EVOLUTION


These domains are part of the current Foundation Architecture scope.

The following domains are planned and are not yet materialized:

07-LEGAL
08-GOVERNANCE
09-AUTOMATION
10-REFERENCE
99-HISTORY

Planned domains shall not be interpreted as missing implementation defects while they remain explicitly classified as planned by the Architecture Map and the active Foundation Normalization Roadmap.

---

# Official Repository Structure

The current structural model is:

```text
BHG-Ecosystem-Foundation/
│
├── ARCHITECTURE_MAP.md
├── README.md
├── LICENSE
├── CHANGELOG.md
├── .gitignore
│
├── docs/
│   │
│   ├── 00-FOUNDATION/
│   ├── 01-IDENTITY/
│   ├── 02-ECOSYSTEM/
│   ├── 03-ORGANIZATION/
│   ├── 04-REPOSITORIES/
│   ├── 05-INTEGRATION/
│   ├── 06-EVOLUTION/
│   │
│   ├── 07-LEGAL/          [PLANNED]
│   ├── 08-GOVERNANCE/     [PLANNED]
│   ├── 09-AUTOMATION/     [PLANNED]
│   ├── 10-REFERENCE/      [PLANNED]
│   └── 99-HISTORY/        [PLANNED]
│
└── assets/
```

The map describes the target structural contract for the current Foundation phase.

A planned directory is not required to exist until its corresponding phase is authorized.

---

# Domain Responsibilities

## 00-FOUNDATION

Defines the permanent institutional foundation of BHG.

Includes:

- manifesto;
- vision;
- mission;
- values;
- principles;
- philosophy.

This domain establishes the conceptual foundation for the rest of the repository.

---

## 01-IDENTITY

Defines institutional identity and naming.

Includes:

- identity model;
- brand architecture;
- corporate language;
- corporate naming standard.

This domain defines how BHG identifies and represents itself.

---

## 02-ECOSYSTEM

Defines the structure and boundaries of the BHG ecosystem.

Includes:

- ecosystem architecture;
- ecosystem model;
- ecosystem layers;
- ecosystem boundaries;
- ecosystem principles.

This domain defines how ecosystem components relate at the architectural level.

---

## 03-ORGANIZATION

Defines the organizational model of BHG.

Includes:

- organization model;
- holding model;
- business capability model;
- business domain model.

This domain defines how institutional capabilities are organized.

---

## 04-REPOSITORIES

Defines repository identity, classification, lifecycle and dependency architecture.

Includes:

- repository registry;
- repository classification;
- repository lifecycle;
- repository dependency model;
- repository naming standard.

This domain provides the repository architecture consumed by future ecosystem automation.

---

## 05-INTEGRATION

Defines relationships and coordination mechanisms between ecosystem repositories.

Includes:

- cross-repository model;
- shared asset model;
- source-of-truth model;
- ecosystem synchronization model.

This domain protects integration without transferring authority between repositories.

---

## 06-EVOLUTION

Defines how BHG evolves in a controlled and measurable manner.

Includes:

- evolution model;
- roadmap model;
- growth model;
- maturity model;
- foundation normalization roadmap.

The Foundation Normalization Roadmap is an execution artifact for the current baseline-preparation phase.

---

# Planned Domains

## 07-LEGAL — Planned

Intended responsibility:

- legal ownership;
- intellectual property;
- licensing;
- legal instruments;
- legal boundaries.

This domain shall not redefine institutional identity or ecosystem architecture.

It shall consume the Foundation architecture and provide legal authority for legal matters.

---

## 08-GOVERNANCE — Planned

Intended responsibility:

- ecosystem-level governance integration;
- governance boundaries;
- governance responsibilities.

This domain shall not replace the existing BHG-Governance repository.

It shall define how governance concepts relate to the broader ecosystem.

---

## 09-AUTOMATION — Planned

Intended responsibility:

- GGC integration;
- ecosystem validation;
- future governance automation interfaces.

The Genesis Governance Compiler shall initially operate as a read-only validation and analysis system.

---

## 10-REFERENCE — Planned

Intended responsibility:

- glossary;
- acronyms;
- institutional references.

This domain shall provide reference material without becoming a competing source of authority.

---

## 99-HISTORY — Planned

Intended responsibility:

- baseline decisions;
- architectural transitions;
- repository history;
- audit evidence;
- institutional evolution records.

Historical records shall preserve evidence and shall not be used to redefine current authority.

---

# Layer Interpretation

The repository currently uses the following conceptual layers:

Identity
    ↓
Foundation
    ↓
Governance
    ↓
Legal
    ↓
Knowledge
    ↓
Technology
    ↓
Business
    ↓
Operations


These layers are conceptual ecosystem layers, not a statement that every layer must be implemented as a directory in this repository.

Repository domains and ecosystem layers are different architectural dimensions.

A directory may represent an architectural domain without being identical to an ecosystem layer.

---

# Dependency Direction

The repository shall preserve the following general direction:


Higher Institutional Authority
            ↓
Foundation Architecture
            ↓
Governance and Domain Models
            ↓
Implementation Architecture
            ↓
Operational Systems


Lower-level implementation shall not redefine higher-level institutional authority.

---

# Authority Rules

## Rule 1 — No Circular Authority

No document may simultaneously depend on and govern its direct authority source.

---

## Rule 2 — Architecture Map Does Not Govern README

`README.md` is the repository entry point.

`ARCHITECTURE_MAP.md` defines the repository architecture.

The two documents may reference each other contextually, but neither shall claim governance authority over the other.

---

## Rule 3 — Architecture Map Does Not Create Legal Authority

This document defines architectural structure only.

Legal authority shall belong to the applicable legal framework.

---

## Rule 4 — Planned Does Not Mean Missing

A planned domain is intentionally not materialized until its phase is authorized.

Planned references shall therefore be distinguished from broken references.

---

## Rule 5 — One Canonical Architecture Map

This repository shall maintain one authoritative root-level `ARCHITECTURE_MAP.md`.

Future repositories may have their own local Architecture Maps.

Each local map shall define only the architecture of its own repository and shall remain compatible with the ecosystem architecture.

---

# Relationship With Other Repositories

`BHG-Ecosystem-Foundation` is one component of the broader BHG repository ecosystem.

Known ecosystem repositories include, at minimum:

BHG-Ecosystem-Foundation
BHG-Governance
BHG-Knowledge
BHG-Legal-Framework    [planned / separate repository]

The existence of a relationship between repositories does not transfer authority.

Each repository remains responsible for its own authoritative information domain.

---

# Source of Truth Boundary

This repository is authoritative for the institutional architecture defined within its approved scope.

It is not authoritative for:

- legal ownership decisions;
- operational governance decisions belonging to BHG-Governance;
- product implementation details;
- external legal instruments.

Cross-repository authority shall be defined through the Source of Truth Model.

---

# Planned Reference Classification

References encountered during normalization shall be classified as:

local
external
planned
deprecated
missing


A planned reference is not a broken reference.

A missing reference is an unresolved dependency requiring remediation.

This distinction shall be enforced by future automated validation.

---

# Foundation Normalization Relationship

This Architecture Map is part of the execution phase defined by:

06-EVOLUTION/FOUNDATION_NORMALIZATION_ROADMAP.md


The roadmap governs the sequence of normalization work.

This Architecture Map defines the repository structure against which that normalization is evaluated.

---

# GGC Readiness

The Architecture Map shall provide structured information required by the Genesis Governance Compiler, including:

- repository scope;
- domain hierarchy;
- planned versus materialized domains;
- dependency direction;
- authority boundaries;
- source-of-truth boundaries.

The GGC may consume this map for validation.

The GGC shall not modify the Architecture Map automatically.

Human governance remains responsible for architectural changes.

---

# Architecture Evolution

Changes to the Architecture Map shall require evaluation of:

- structural impact;
- authority impact;
- dependency impact;
- repository impact;
- historical continuity.

Architecture changes shall be documented and version-controlled.

---

# Compliance

The repository shall be considered architecturally compliant when:

- every materialized domain is declared;
- planned domains are explicitly classified;
- repository boundaries are documented;
- dependency direction is defined;
- authority relationships remain acyclic;
- root structure matches the approved map.

---

# Institutional Principle

> Architecture defines where institutional responsibility lives.

> Clear boundaries make growth possible without creating ambiguity.

> A reliable ecosystem begins with a reliable map of itself.
