---
title: Repository Naming Standard
document_id: REPOSITORY_NAMING_STANDARD
version: 1.0.0
status: Approved
document_type: Repository Governance Standard
governance_level: Foundation
owner: BHG Ecosystem Foundation
approval_authority: BHG Governance Council
created: 2026-07-24
last_updated: 2026-07-24
effective_date: 2026-07-24
classification: Internal
language: en
repository: BHG-Ecosystem-Foundation

governed_by:
  - BHG_CONSTITUTION.md
  - FOUNDATION_MANIFESTO.md
  - ECOSYSTEM_ARCHITECTURE.md
  - REPOSITORY_REGISTRY.md
  - REPOSITORY_CLASSIFICATION.md

governs:
  - Repository Naming Rules
  - Repository Identification Standards
  - Repository Naming Consistency
  - Repository Naming Validation

depends_on:
  - REPOSITORY_REGISTRY.md
  - REPOSITORY_CLASSIFICATION.md
  - ECOSYSTEM_MODEL.md

related_to:
  - REPOSITORY_DEPENDENCY_MODEL.md
  - CROSS_REPOSITORY_MODEL.md
  - SOURCE_OF_TRUTH_MODEL.md
  - GGC_INTEGRATION_MODEL.md
---

# Repository Naming Standard

> Official naming framework for repositories belonging to the Breto's Holding Group ecosystem.

---

# Purpose

The Repository Naming Standard defines the official rules used to identify repositories inside the BHG ecosystem.

Its purpose is to guarantee that every repository name communicates:

- institutional ownership;
- ecosystem relationship;
- functional purpose;
- architectural role.

A repository name is considered an institutional identifier.

It is not only a technical label.

---

# Naming Authority

Repository naming standards define identity conventions.

They do not define:

- repository ownership;
- legal ownership;
- governance authority;
- approval rights.

These responsibilities remain defined by:

- BHG Governance Framework;
- Legal Framework;
- Repository Registry;
- Authority Model.

---

# Naming Principles

## Principle 1 — Every Repository Has a Unique Name

Every official repository shall have a unique identifier within the BHG ecosystem.

Duplicate repository names are prohibited.

---

## Principle 2 — Names Must Communicate Purpose

Repository names shall provide meaningful information about their role.

Names should allow understanding of:

- domain;
- capability;
- institutional relationship.

---

## Principle 3 — Names Must Remain Stable

Repository names represent institutional identity.

Changing a repository name requires evaluation of:

- dependencies;
- references;
- integrations;
- historical continuity.

---

## Principle 4 — Names Must Be Machine Compatible

Repository names shall support:

- automation;
- validation;
- indexing;
- graph analysis.

---

## Principle 5 — Names Must Preserve Institutional Identity

Official repositories shall reflect their relationship with BHG.

Naming shall avoid ambiguity with unrelated external assets.

---

# Repository Naming Structure

The standard BHG repository naming pattern is:


BHG-[DOMAIN]-[PURPOSE]


or:


BHG-[PRODUCT]


depending on repository classification.

---

# Naming Components

Repository names may contain:

## Organization Prefix

Identifies institutional belonging.

Standard prefix:


BHG


Example:


BHG-Governance


---

## Domain Identifier

Identifies the ecosystem area.

Examples:


GOVERNANCE
LEGAL
KNOWLEDGE
ECOSYSTEM
ENGINEERING
PRODUCT


---

## Purpose Identifier

Identifies the repository function.

Examples:


Framework
Platform
Core
Foundation
OS
Engine
Registry


---

# Official Naming Pattern Examples

Examples of valid repository names:


BHG-Governance

BHG-Knowledge

BHG-Legal-Framework

BHG-Ecosystem-Foundation

BHG-Genesis-Governance-Compiler

BHG-Ziva-Core


---

# Invalid Naming Examples

The following patterns are discouraged:


test-project

my-app

new-system

random-repo

version2-final


Reasons:

- no institutional context;
- unclear purpose;
- poor maintainability;
- weak automation compatibility.

---

---

# Repository Name Categories

Repository names shall align with the official repository classification model.

The repository category influences naming conventions.

---

# Governance Repository Naming

Governance repositories contain institutional governance frameworks.

Recommended pattern:


BHG-Governance-[Purpose]


Examples:


BHG-Governance

BHG-Governance-Compiler

BHG-Governance-Audit


Governance repositories should communicate:

- authority;
- institutional responsibility;
- governance function.

---

# Knowledge Repository Naming

Knowledge repositories preserve institutional information.

Recommended pattern:


BHG-Knowledge-[Purpose]


Examples:


BHG-Knowledge

BHG-Knowledge-Base

BHG-Knowledge-Research


Knowledge repositories should communicate:

- information domain;
- learning purpose;
- preservation role.

---

# Legal Repository Naming

Legal repositories contain ownership and legal frameworks.

Recommended pattern:


BHG-Legal-[Purpose]


Examples:


BHG-Legal-Framework

BHG-Legal-Intellectual-Property

BHG-Legal-Contracts


Legal repositories should clearly identify protected institutional domains.

---

# Ecosystem Repository Naming

Ecosystem repositories define broad organizational structures.

Recommended pattern:


BHG-Ecosystem-[Purpose]


Examples:


BHG-Ecosystem-Foundation

BHG-Ecosystem-Architecture


These repositories represent high-level institutional assets.

---

# Engineering Repository Naming

Engineering repositories contain technical systems.

Recommended pattern:


BHG-Engineering-[Purpose]


Examples:


BHG-Engineering-Standards

BHG-Engineering-Tools


---

# Product Repository Naming

Product repositories represent products, platforms or services.

Recommended pattern:


BHG-[ProductName]


Examples:


BHG-Ziva

BHG-Ziva-Platform

BHG-Ziva-Core


Product names shall follow the Corporate Naming Standard.

---

# Compiler and Automation Naming

Systems that execute institutional automation shall use explicit functional names.

Recommended pattern:


BHG-[Domain]-[Engine]


Examples:


BHG-Genesis-Governance-Compiler

BHG-Documentation-Compiler

BHG-Validation-Engine


The term:


Engine


identifies an execution component.

---

# Naming Rules

## Rule 1 — Use Pascal Case for Institutional Components

Repository components shall use Pascal Case.

Correct:


BHG-Ecosystem-Foundation


Incorrect:


BHG-ecosystem-foundation


---

## Rule 2 — Avoid Technical Implementation Names

Repository names shall represent institutional purpose.

Avoid:


BHG-React-App
BHG-NextJS-Test
BHG-Node-Service


because technologies may change.

---

## Rule 3 — Avoid Temporary Names

Temporary identifiers shall not become official repositories.

Avoid:


BHG-New
BHG-Test
BHG-Version2


---

## Rule 4 — Avoid Personal Names

Repositories should represent institutional assets.

Avoid:


LuisProject
BretoCode
LuisExperiments


unless explicitly defined as personal research repositories.

---

## Rule 5 — Preserve Historical Identity

Renaming requires preservation of:

- previous name;
- rename date;
- reason;
- migration impact.

---

# Repository Identifier Standard

Every repository shall have an internal identifier independent from its display name.

Example:

```yaml
repository_id:
  BHG-ECO-FND-001

repository_name:
  BHG-Ecosystem-Foundation

The identifier provides:

stable reference;
automation compatibility;
historical continuity.
Repository Identifier Format

The recommended identifier pattern is:

BHG-[DOMAIN]-[SEQUENCE]

Example:

BHG-GOV-001

BHG-KNO-001

BHG-LEG-001
Domain Identifier Codes

Recommended codes:

Domain	Code
Governance	GOV
Knowledge	KNO
Legal	LEG
Ecosystem	ECO
Engineering	ENG
Product	PRD
Research	RES
Automation	AUT
Naming Registry

All official repository names shall be registered through the Repository Registry.

The Registry shall maintain:

repository identifier;
official name;
previous names;
naming rationale;
classification;
lifecycle state.

---

# Repository Naming Validation

Repository names shall be validated before official recognition.

Validation shall verify:

- naming format;
- uniqueness;
- classification alignment;
- institutional consistency;
- automation compatibility.

---

# Naming Validation Rules

## Identity Validation

The validator shall verify:

- repository identifier exists;
- repository name is unique;
- repository naming record exists.

---

## Format Validation

The validator shall verify:

- approved prefix usage;
- correct separator format;
- prohibited characters;
- naming convention compliance.

---

## Classification Alignment Validation

The repository name shall be consistent with its classification.

Example:

A repository classified as Legal Repository should not use a name that suggests an unrelated technical purpose.

Invalid example:


BHG-Legal-Frontend


---

## Ecosystem Alignment Validation

The validator shall verify that repository names:

- belong to BHG naming structures;
- do not create ecosystem ambiguity;
- preserve institutional identity.

---

# Genesis Governance Compiler Integration

The Genesis Governance Compiler (GGC) shall use repository naming standards as part of repository architecture validation.

The GGC may analyze:

- naming compliance;
- duplicate names;
- inconsistent naming patterns;
- classification conflicts;
- repository identity integrity.

The GGC may generate:

- naming validation reports;
- repository identity reports;
- architecture consistency findings.

---

The GGC shall not:

- rename repositories automatically;
- approve naming exceptions;
- modify repository identity records;
- override governance decisions.

Human governance remains the final authority.

---

# Repository Rename Management

Repository renaming is considered an institutional change.

A rename process shall evaluate:

- dependency impact;
- external references;
- documentation references;
- automation configurations;
- historical continuity.

---

# Rename Lifecycle

A repository rename shall follow:


Rename Proposal

    ↓

Impact Analysis

    ↓

Governance Review

    ↓

Approval Decision

    ↓

Repository Rename

    ↓

Reference Update

    ↓

Historical Registration


---

# Rename Historical Record

Every rename shall preserve:

```yaml
repository_name_history:

  previous_name:

  new_name:

  change_date:

  reason:

  approved_by:

  migration_completed:

Historical names shall never be deleted.

They represent institutional evolution.

Repository Naming Exceptions

Exceptions may exist when justified by:

legal requirements;
acquired intellectual property;
established external identity;
strategic considerations.

Every exception requires:

documented justification;
governance review;
approval authority;
historical record.
Repository Naming Security

Repository naming protects institutional identity.

Controls shall include:

reserved naming patterns;
duplicate detection;
unauthorized rename prevention;
historical preservation.

Unauthorized naming changes may create:

identity confusion;
dependency failures;
governance inconsistencies.
Repository Naming Evolution

The naming standard shall evolve according to:

ecosystem expansion;
organizational changes;
new business domains;
technological evolution.

Future improvements may include:

automated naming recommendations;
semantic naming validation;
AI-assisted repository classification;
naming intelligence systems.

Evolution shall preserve:

clarity;
consistency;
institutional identity.
Repository Naming Compliance

A repository shall be considered naming compliant when:

it follows the naming standard;
it has a unique identifier;
it is registered;
it matches its classification;
it preserves historical records;
it passes validation requirements.
Non-Compliance Conditions

The following conditions represent naming non-compliance:

duplicate repository names;
undocumented renames;
misleading names;
invalid naming structures;
missing repository identifiers;
unauthorized naming changes.

Non-compliant repositories shall enter remediation.

Completion of Repository Architecture Domain

With this standard, the repository architecture foundation is complete.

The repository management framework now contains:

04-REPOSITORIES

├── REPOSITORY_REGISTRY.md
│
├── REPOSITORY_CLASSIFICATION.md
│
├── REPOSITORY_LIFECYCLE.md
│
├── REPOSITORY_DEPENDENCY_MODEL.md
│
└── REPOSITORY_NAMING_STANDARD.md

These documents establish:

repository identity;
repository purpose;
repository categories;
repository evolution;
repository relationships;
repository naming;
automation readiness.
Future Integration Capability

The completed repository architecture enables:

repository inventory management;
ecosystem dependency graphs;
automated compliance verification;
Genesis Governance Compiler analysis;
cross-repository governance.
Institutional Principle

A repository name is the identity of an institutional asset.

Consistent naming preserves discoverability, governance and long-term ecosystem continuity.


---
