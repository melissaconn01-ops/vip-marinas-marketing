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
                - If AI is helping maintain this repo, provide the relevant CSV row or Markdown section and ask for a specific update.
