# VIP Marinas Marketing — Project Management Repository

## Purpose

This repository is the source of truth for VIP Marinas marketing project management. It is organized to keep all campaign work, website updates, tracking issues, and leadership follow-up in one clean, accessible place.

## How This Repo Is Organized

The workflow follows a simple three-level hierarchy:

**Marina → Project Topic → Managed Task / Item**

- **Marina** is the top level. Each marina has its own folder under `marinas/`.
- **Project Topic** is the second level. Inside each marina folder is a `projects/` subfolder with a Markdown file for each active project or focus area.
- **Managed Task / Item** is the third level. Individual tasks, action items, approvals, blockers, and next steps are tracked in the CSV files at the root level.

## File Types

**Markdown files** (`.md`) hold project notes, context, background, open questions, and latest updates. They are the working documents for each project.

**CSV files** (`.csv`) hold spreadsheet-style trackers. They can be opened in Excel, Google Sheets, or reviewed directly on GitHub.

---

## Root-Level Files

| File | Purpose |
|---|---|
| `README.md` | This file. Overview and guide to the repo. |
| `project-updates.md` | Working log for meeting notes, changes, and updates. Use this as the messy working doc. |
| `marina-index.csv` | Portfolio-level tracker for all marinas. |
| `project-index.csv` | Tracks all major projects by marina. |
| `project-tasks.csv` | Tracks specific action items, approvals, blockers, and next steps. |
| `campaign-tracker.csv` | Tracks marketing campaigns across marinas. |
| `tracking-issues.csv` | Tracks conversion tracking, lead tracking, GA4, Google Ads, phone, form, Kenect, and CRM issues. |

---

## Marina Folders

Each marina has a folder under `marinas/` with the following structure:

```
marinas/
└── marina-name/
    ├── overview.md         ← Marina-level marketing overview
        └── projects/
                └── project-name.md ← One file per project or focus area
                ```

                ### Current Marinas

                | Marina | Folder | Status |
                |---|---|---|
                | Lake Travis | `marinas/lake-travis/` | Active |
                | Bluff House | `marinas/bluff-house/` | Active |
                | Meridian | `marinas/meridian/` | Active |
                | Anclote | `marinas/anclote/` | Needs Review |

                ---

                ## How to Use This Repo

                1. **For new updates or meeting notes** → Add an entry to `project-updates.md`
                2. **For project status** → Check `project-index.csv`
                3. **For individual tasks and action items** → Check `project-tasks.csv`
                4. **For campaign details** → Check `campaign-tracker.csv`
                5. **For tracking issues** → Check `tracking-issues.csv`
                6. **For marina-specific context** → Open the relevant `overview.md` or project file under `marinas/`

                ---

                ## Maintenance Notes

                - Keep `project-updates.md` as the loose working log. It does not need to be perfectly organized.
                - Keep CSVs as the structured source of truth. Update them when statuses, owners, or priorities change.
                - Keep Markdown project files for context, background, decisions, and notes that do not fit in a spreadsheet cell.

---

## Reporting Workflow

This repository uses a simple AI-assisted reporting workflow to keep the portfolio organized and visible.

1. **User provides updates through AI.** Meeting notes, status changes, new tasks, and decisions are communicated to the AI in plain language.
2. **AI updates project files and trackers.** The AI edits the relevant CSV rows, markdown files, or dashboard files based on the updates provided.
3. **GitHub remains the source of truth.** All committed changes in this repository are authoritative. CSV files and project markdown files are the primary record.
4. **AI can generate reports from repository data.** When needed, the AI can read CSV and markdown files and generate summaries, dashboards, or status reports.
5. **Dashboard files provide a human-readable layer.** The dashboard.md, current-priorities.md, leadership-review.md, and weekly-summary.md files translate tracker data into readable summaries.
6. **Future integrations can consume data from the repository.** Airtable, Google Drive, custom dashboards, and other tools can be connected to consume this repository's data without replacing it as the source of truth.

---

## Reporting and Dashboard Files

| File | Purpose |
|------|---------|
| dashboard.md | Portfolio-wide operational dashboard. AI-generated. Refresh regularly. |
| current-priorities.md | Most important active work across the portfolio. Update when priorities change. |
| leadership-review.md | Items requiring leadership review, approval, direction, or escalation. |
| weekly-summary.md | Weekly summary of meaningful changes. Update weekly. |
| reports/ | Folder for AI-generated reports and periodic summaries. |

---

## Status Values

Use these standard values across all CSV trackers for consistency.

### Project Status
- Not Started
- Planning
- In Progress
- Needs Review
- Waiting on Approval
- Blocked
- Completed
- Paused

### Task Status
- Not Started
- In Progress
- Needs Review
- Waiting on Someone
- Blocked
- Completed
- Deferred

### Priority
- High
- Medium
- Low
- If AI is helping maintain this repo, provide the relevant CSV row or Markdown section and ask for a specific update.

---

## AI Project Management Rules

These rules govern how AI should manage this repository. They apply to all edits, updates, and reporting tasks.

### Read Before Write

AI must read the relevant files before editing them. Do not assume the current state of a file without reading it first.

### Approval Before Commit

The default workflow is:

1. AI reads relevant files.
2. AI proposes updates.
3. User approves.
4. AI commits changes.

Auto-commit is allowed only when the user explicitly says so.

### Read-After-Write Verification

After committing, AI should re-open the updated files and verify that the expected rows, files, or sections were created correctly.

### Failed Update Reporting

If any file update fails or is blocked, AI must include a "Failed or Skipped Updates" section in its summary before finishing.

### Dashboard Refresh Rule

After meaningful project, campaign, task, or tracking updates, AI should refresh the following files when relevant:

- dashboard.md
- current-priorities.md
- leadership-review.md
- weekly-summary.md

### Event Project Rule

For event projects, AI should update all of the following that apply:

- project-index.csv
- project-tasks.csv
- campaign-tracker.csv (if promotion is involved)
- tracking-issues.csv (if registration or source tracking is needed)
- event-tracker.csv
- Marina project Markdown file
- Dashboard and reporting files

### Cross-Property Project Rule

If a project involves more than one marina, use Related Project ID fields in project-index.csv and campaign-tracker.csv to connect the projects.

Example: MER-EVT-001 relates to BH-EVT-001, and BH-EVT-001 relates to MER-EVT-001.
- Low
                - If AI is helping maintain this repo, provide the relevant CSV row or Markdown section and ask for a specific update.
