# VAYRA OS Enterprise
# Naming Convention Standard

Version: 1.0
Status: Production
Document Type: Architecture Standard
Module: 00_ARCHITECTURE

---

# Purpose

This document defines the official naming conventions for folders, files, AI agents, workflows, SOPs, templates, checklists, and other repository assets within VAYRA OS Enterprise.

Consistent naming improves readability, discoverability, automation, and AI comprehension while ensuring the repository remains organized as it grows.

---

# Objectives

The Naming Convention Standard aims to:

- Standardize names across the repository.
- Improve searchability.
- Simplify navigation.
- Support automation.
- Reduce ambiguity.
- Maintain enterprise consistency.

---

# General Principles

Every name should be:

- Clear
- Descriptive
- Consistent
- Human-readable
- AI-readable
- Unique
- Scalable

Avoid abbreviations unless they are widely accepted within the organization.

---

# Folder Naming Standard

Rules:

- Use Pascal_Case.
- Separate words using underscores (_).
- Do not use spaces.
- Do not use special characters.
- Prefix root folders with numbers where applicable.

Examples:

✔️ 30_AI_AGENTS

✔️ 07_PROJECT_MANAGEMENT

✔️ Client_Templates

❌ AI Agents

❌ project-management

❌ project management

---

# File Naming Standard

Rules:

- Use Pascal_Case.
- Separate words with underscores.
- Use descriptive names.
- Keep filenames concise.

Examples:

Mission.md

Responsibilities.md

Decision_Authority.md

Strategic_Planning.md

Client_Handover.md

Financial_Review.md

---

# README Naming

Every folder should contain:

README.md

Only one README is permitted per folder.

---

# AI Agent Naming

Agent names should represent business roles.

Examples:

CEO

COO

CDO

Project_Manager

Finance

HR

Marketing

Senior_Interior_Designer

2D_Draftsman

3D_Visualizer

---

# Workflow Naming

Workflow names should describe the business process.

Examples:

Strategic_Planning.md

Project_Approval.md

Client_Onboarding.md

Budget_Review.md

Risk_Assessment.md

Site_Inspection.md

Avoid generic names such as:

Workflow1.md

New_Process.md

Final_Workflow.md

---

# SOP Naming

SOP names should begin with "SOP_".

Examples:

SOP_Project_Approval.md

SOP_Client_Handover.md

SOP_Budget_Control.md

SOP_Quality_Assurance.md

---

# Template Naming

Templates should end with "_Template".

Examples:

Workflow_Template.md

Proposal_Template.md

Quotation_Template.md

Meeting_Minutes_Template.md

Prompt_Template.md

---

# Checklist Naming

Checklist documents should end with "_Checklist".

Examples:

Site_Visit_Checklist.md

Hiring_Checklist.md

Project_Closure_Checklist.md

Client_Handover_Checklist.md

---

# Version Naming

Document versions should follow semantic versioning.

Examples:

1.0

1.1

1.2

2.0

Major Version

Breaking structural changes.

Minor Version

New content or enhancements.

Patch Version

Minor corrections.

---

# Date Format

Use ISO 8601 format.

YYYY-MM-DD

Example:

2026-07-19

---

# Numbering Standards

Reserve numbering ranges for major modules.

00–09 → Foundation

10–19 → Knowledge Base

20–29 → Shared Resources

30–39 → AI Runtime

40–49 → Operations

50–59 → Automation

---

# Reserved Words

Do not use:

New

Final

Latest

Temp

Copy

Draft

Test

Misc

Untitled

Use meaningful names instead.

---

# Deprecated Files

Deprecated documents should be moved to an Archive folder rather than renamed.

Example:

Archive/

Old_Strategic_Plan.md

Deprecated_Workflow.md

---

# Naming Examples

Correct:

30_AI_AGENTS/

CEO/

Workflows/

Strategic_Planning.md

Incorrect:

AI Folder/

workflow.md

New File.md

final_version2.md

---

# Compliance Rules

Every contributor must:

- Follow naming standards.
- Use approved formats.
- Avoid duplicate names.
- Maintain consistency.
- Update references after renaming files.

---

# Success Criteria

The naming system is successful when it is:

- Predictable
- Searchable
- Consistent
- Human-readable
- AI-friendly
- Easy to maintain
- Enterprise-ready

---

# Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | 2026-07-19 | Initial naming convention standard. |

---

End of Document
