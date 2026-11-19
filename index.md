---
layout: default
title: S Concourse Evolution Knowledge Repository
---

# S Concourse Evolution Knowledge Repository

This site is the navigation index for the S Concourse Evolution project context package. The repository supports consistent, traceable design reviews focused on aircraft operations, gate and apron capacity, life safety, stakeholder requirements, construction phasing, and lessons learned.

> **Evidence status:** This index is based on the repository inventory supplied on November 19, 2026. The listed files are known to exist, but their contents were not retrieved during preparation of this page. File descriptions below are therefore based on filenames and remain provisional until content validation is completed.

## Start here

- [Repository README](README.md) – Repository purpose, structure, and use.
- [Project Context](S_Concourse_Evolution_Context_Package/00_PROJECT_CONTEXT.md) – Core program background, scope, stakeholders, and project setting.
- [Project-Specific Context](S_Concourse_Evolution_Context_Package/05_PROJECT_SPECIFIC_CONTEXT.md) – Current S Concourse conditions, constraints, interfaces, and assumptions.
- [Aircraft Operations Design Principles](S_Concourse_Evolution_Context_Package/08_AIRCRAFT_OPERATIONS_DESIGN_PRINCIPLES.md) – Operational and capacity principles that should lead design decisions.
- [Decision Log](S_Concourse_Evolution_Context_Package/09_DECISION_LOG.md) – Record of project decisions, rationale, authority, and status.

## Project foundation

### [00 – Project Context](S_Concourse_Evolution_Context_Package/00_PROJECT_CONTEXT.md)

Use this file for the program overview, scope boundaries, stakeholder map, existing conditions, and general project assumptions.

### [01 – Standards and Criteria](S_Concourse_Evolution_Context_Package/01_STANDARDS_AND_CRITERIA.md)

Use this file to track applicable FAA advisory circulars, Port standards, Fire Department criteria, airline requirements, project criteria, revisions, interpretations, and unresolved compliance questions.

For airport geometry, aircraft compatibility, apron, and taxilane reviews, confirm the applicable revision and project interpretation of **FAA AC 150/5300-13B, Airport Design**. For construction phasing and temporary operational conditions, confirm the applicable revision and project interpretation of **FAA AC 150/5370-2G, Operational Safety on Airports During Construction**.

### [02 – Client Preferences](S_Concourse_Evolution_Context_Package/02_CLIENT_PREFERENCES.md)

Use this file for documented Port preferences, review expectations, presentation conventions, decision protocols, and recurring coordination needs. Distinguish preferences from mandatory requirements.

## Lessons and repeatable review knowledge

### [03 – Lessons Learned](S_Concourse_Evolution_Context_Package/03_LESSONS_LEARNED.md)

Use this file for applicable IAF/A6 lessons and new S Concourse lessons. Each lesson should include context, trigger, impact, recommended practice, applicability, and source evidence.

### [04 – Common Review Comments](S_Concourse_Evolution_Context_Package/04_COMMON_REVIEW_COMMENTS.md)

Use this file for recurring comments and review checks. Comments should identify the operational, capacity, life-safety, compliance, constructability, maintainability, schedule, or cost consequence.

### [07 – AI Insights](S_Concourse_Evolution_Context_Package/07_AI_INSIGHTS.md)

Use this file for synthesized patterns, cross-file observations, unresolved questions, and proposed updates. Treat generated insights as analysis until validated against project evidence and accepted by the appropriate decision authority.

## Project review record

### [05 – Project-Specific Context](S_Concourse_Evolution_Context_Package/05_PROJECT_SPECIFIC_CONTEXT.md)

Use this file for S Concourse-specific operational baselines, capacity metrics, stakeholder constraints, design interfaces, construction conditions, and open issues.

### [06 – Review History](S_Concourse_Evolution_Context_Package/06_REVIEW%20HISTORY.md)

Use this file for review dates, packages reviewed, milestone decisions, findings, responses, closure status, and source references.

> **Filename note:** This filename contains a space. The encoded link above is GitHub Pages-compatible. Renaming the file to `06_REVIEW_HISTORY.md` is recommended for consistency and simpler future linking. If renamed, update this index in the same commit.

### [08 – Aircraft Operations Design Principles](S_Concourse_Evolution_Context_Package/08_AIRCRAFT_OPERATIONS_DESIGN_PRINCIPLES.md)

Use this file to establish and preserve the operational baseline for gates, aircraft parking, apron circulation, taxilanes, passenger processing, baggage, emergency access, and construction continuity.

### [09 – Decision Log](S_Concourse_Evolution_Context_Package/09_DECISION_LOG.md)

Use this file as the auditable record of decisions. Each entry should identify the issue, alternatives, operational and capacity effects, decision, rationale, decision authority, date, evidence, and any conditions for closure.

## Complete Markdown inventory

The inventory contains **12 Markdown files**: two files at the repository root and ten files in the context package.

### Repository root

1. [README.md](README.md)
2. [index.md](index.md) – This page

### Context package

1. [00_PROJECT_CONTEXT.md](S_Concourse_Evolution_Context_Package/00_PROJECT_CONTEXT.md)
2. [01_STANDARDS_AND_CRITERIA.md](S_Concourse_Evolution_Context_Package/01_STANDARDS_AND_CRITERIA.md)
3. [02_CLIENT_PREFERENCES.md](S_Concourse_Evolution_Context_Package/02_CLIENT_PREFERENCES.md)
4. [03_LESSONS_LEARNED.md](S_Concourse_Evolution_Context_Package/03_LESSONS_LEARNED.md)
5. [04_COMMON_REVIEW_COMMENTS.md](S_Concourse_Evolution_Context_Package/04_COMMON_REVIEW_COMMENTS.md)
6. [05_PROJECT_SPECIFIC_CONTEXT.md](S_Concourse_Evolution_Context_Package/05_PROJECT_SPECIFIC_CONTEXT.md)
7. [06_REVIEW HISTORY.md](S_Concourse_Evolution_Context_Package/06_REVIEW%20HISTORY.md)
8. [07_AI_INSIGHTS.md](S_Concourse_Evolution_Context_Package/07_AI_INSIGHTS.md)
9. [08_AIRCRAFT_OPERATIONS_DESIGN_PRINCIPLES.md](S_Concourse_Evolution_Context_Package/08_AIRCRAFT_OPERATIONS_DESIGN_PRINCIPLES.md)
10. [09_DECISION_LOG.md](S_Concourse_Evolution_Context_Package/09_DECISION_LOG.md)

## Repository quality checks

| Check | Status | Required action |
|---|---|---|
| Known Markdown files linked | Complete | All 12 inventoried files are linked from this page. |
| Duplicate inventory paths | None identified | Recheck whenever files are added or renamed. |
| Filename consistency | One exception | Consider renaming `06_REVIEW HISTORY.md` to `06_REVIEW_HISTORY.md`. |
| File-content validation | Not complete | Retrieve and review all context files before relying on descriptions or making design conclusions. |
| Requirements traceability | Not verified | Confirm citations, revisions, interpretations, and approval authorities in the standards file. |
| IAF/A6 lesson applicability | Not verified | Map each relevant lesson to current S Concourse design evidence. |
| Operational and capacity baseline | Not verified | Confirm gates, apron, taxilanes, passenger processing, baggage, emergency access, and phasing conditions. |

## Expected future repository records

The following records are not separate files in the supplied inventory. These subjects may already be sections within the listed files, so their status must be confirmed during content review:

- Requirements traceability matrix
- Risk register
- Open-issues and action log
- Drawing register
- Specification register
- Stakeholder approval and interpretation log
- Construction Safety and Phasing Plan review record
- Aircraft compatibility and gate-capacity assessment

If these records grow beyond a manageable section, create dedicated Markdown files and add them to this index.

## Review-use protocol

Before a substantive design review:

1. Confirm every listed repository file is available and readable.
2. Identify the design package, milestone, review scope, and decision deadline.
3. Establish the existing and target aircraft-operations and capacity baseline.
4. Verify applicable FAA, Port, Fire Department, and airline requirements.
5. Apply relevant IAF/A6 lessons and record applicability.
6. Separate blockers, required design changes, recommendations, and observations.
7. Record evidence, operational consequence, owner or decision authority, and closure criterion for each finding.
8. Update the review history, decision log, lessons learned, risks, and requirements traceability as applicable.

## GitHub Pages publishing

This file is configured for publication as the repository-root Pages index.

1. Commit `index.md` to the `main` branch at the repository root.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Save the configuration and allow the **pages build and deployment** workflow to finish.
6. Verify the published site at [SCE GitHub Pages](https://dnguyen8541.github.io/SCE/).
7. After any filename change, test every link from the published page, not only from the GitHub repository preview.

---

**Index basis:** `MARKDOWN-INVENTORY.txt`, supplied November 19, 2026.  
**Repository:** SCE  
**Branch:** `main`  
**Index status:** Complete for the supplied path inventory; provisional for file content and design evidence.
