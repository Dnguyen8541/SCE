---
layout: default
title: Document Source Register
---

# Document Source Register

## Purpose

This register identifies the persistent knowledge sources available to the S Concourse Evolution agent and records the drawing, specification, criteria, and review packages used for design reviews.

The register is an index and traceability record. It does not make GitHub the master repository for drawings or specifications.

## Persistent Agent Knowledge Architecture

| Layer | Platform | Purpose | Status |
|---|---|---|---|
| Project document corpus | Private SharePoint site and document library | Searchable drawings, specifications, narratives, requirements, and review packages available to the S Concourse agent | To be configured |
| Curated project knowledge | `dnguyen8541/SCE` | Program context, standards, preferences, lessons, project-specific context, review history, design principles, decisions, and this source register | Active |
| Review workspace | Review-specific chat and approved markup environment | Package review, findings, markups, responses, and closeout | Per review |

## SharePoint Knowledge Source

Complete this section after the private SharePoint source is created and connected to the agent.

- **Site name:** S Concourse Evolution Agent Knowledge
- **Library name:** Design Knowledge
- **Site URL:** Internal/private; do not publish on GitHub Pages
- **Agent knowledge-source name:** SCE Design Knowledge
- **Connection status:** Pending
- **Last connection validation:** Pending
- **Knowledge owner:** David Nguyen

## Recommended Library Structure

```text
Design Knowledge/
├── 00_Agent_Context/
├── 01_Current_Design_Basis/
│   ├── Drawings/
│   └── Specifications/
├── 02_Review_Packages/
├── 03_Stakeholder_Requirements/
├── 04_IAF_A6_Reference/
├── 05_Review_Outputs/
└── 99_Superseded/
```

## Source Authority Rules

1. Use SharePoint metadata to identify current and superseded documents.
2. Do not assume the most recently uploaded file is controlling.
3. Confirm package, milestone, revision, issue date, and status before a review.
4. Record every file actually retrieved for a review.
5. Identify expected files that were unavailable or unreadable.
6. Label conclusions provisional when the evidence set is incomplete.
7. Keep superseded packages available for traceability but excluded from current-design retrieval where practical.
8. Store reviewable, text-searchable PDFs for agent retrieval even when native CAD or BIM files are retained elsewhere.
9. Do not publish private SharePoint URLs, access tokens, controlled information, or sensitive source documents on the public GitHub Pages site.

## Required SharePoint Metadata

| Field | Purpose |
|---|---|
| Document Type | Drawing, specification, narrative, requirement, lesson, decision, review output, or other record |
| Discipline | Civil/airfield, architecture, structural, mechanical, electrical, fueling, special systems, or other discipline |
| Package/Milestone | Package and design milestone, such as 90%, IFC, addendum, or bulletin |
| Revision | Source revision identifier |
| Issue Date | Formal issue date |
| Status | Current, superseded, draft, under review, or record |
| Review Status | Not reviewed, in review, reviewed, response pending, or closed |
| Source Organization | Organization that issued the document |
| Document Number | Drawing, specification, or document identifier |
| Security Classification | Distribution or sensitivity classification |
| Supersedes | Prior file or revision replaced by the current item |
| GitHub Review Record | Related review-history or decision-log reference |
| SHA-256 | Optional checksum for confirming the exact reviewed file |

## Drawing Package Register

| Package | Discipline | File or Document ID | Revision | Issue Date | Status | Agent Source | Review Record | Notes |
|---|---|---|---|---|---|---|---|---|
| Pending | Pending | Pending | Pending | Pending | Pending | Pending | Pending | Populate after SharePoint upload |

## Specification Package Register

| Package | Division or Volume | File or Document ID | Revision | Issue Date | Status | Agent Source | Review Record | Notes |
|---|---|---|---|---|---|---|---|---|
| Pending | Pending | Pending | Pending | Pending | Pending | Pending | Pending | Populate after SharePoint upload |

## Stakeholder and Criteria Register

| Source | Subject | Revision or Date | Status | Agent Source | Notes |
|---|---|---|---|---|---|
| Pending | FAA criteria | Pending | Pending | Pending | Verify revision, change, errata, and project interpretation before use |
| Pending | Airport Operations | Pending | Pending | Pending | Record approval or interpretation authority |
| Pending | Fire Department | Pending | Pending | Pending | Record approval or interpretation authority |
| Pending | Airline requirements | Pending | Pending | Pending | Record airline and affected gates or operations |

## Review Package Intake Checklist

For each formal review, record:

- Package title and milestone
- Issue date and revision
- Date received
- Source organization
- Expected drawing and specification list
- Files retrieved successfully
- Missing or unreadable files
- Current/superseded status
- Applicable stakeholder requirements
- Related IAF/A6 lessons
- Review chat or review-record identifier
- SHA-256 checksums when exact file verification is needed

## Agent Retrieval Instruction

For each substantive review, direct the agent to:

1. Use this register and the persistent SCE context sources.
2. Retrieve the explicitly identified review-package folder.
3. Report every file successfully retrieved.
4. Report expected files that were unavailable.
5. Confirm milestone, revision, issue date, and status.
6. Treat aircraft operations and capacity preservation as leading criteria.
7. Label the review provisional when required evidence is incomplete.
8. Recommend updates to this register when new packages, revisions, or knowledge sources are added.

## Change Log

| Date | Change | Author | Status |
|---|---|---|---|
| 2026-11-19 | Initial register created for the persistent SharePoint-to-agent knowledge architecture | David Nguyen | Proposed |
