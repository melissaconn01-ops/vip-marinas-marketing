# Data Quality Check

**Purpose:** Flag incomplete, inconsistent, or risky project data in the VIP Marinas marketing repository.

AI should run a data quality check after major project updates.

Last updated: 2026-06-03

---

## Checks to Run

### Projects
- Projects missing owners
- Projects missing next steps
- Projects missing related Markdown files
- project-index.csv rows pointing to missing Markdown files
- Markdown project files not linked in project-index.csv
- Projects requiring approval but not listed in leadership-review.md

### Tasks
- Tasks missing owners
- Tasks missing due dates
- Tasks marked high priority with no next step

### Campaigns
- Campaigns missing landing pages
- Campaigns missing related project IDs
- Campaigns missing tracking requirements

### Tracking Issues
- Tracking issues missing next steps

### Events
- Events missing registration deadlines
- Events missing tracking requirements

---

## Current Flags

| Flag | File / Location | Status |
|---|---|---|
| marinas/meridian/overview.md needed update after MER-EVT-001 was created | marinas/meridian/overview.md | Resolved 2026-06-03 |
| Dashboard and reporting files not refreshed after MER-EVT-001 was created | Multiple .md files | Resolved 2026-06-03 |
| Welcome Party date for Meridian Bahamas Run needs verification | event-tracker.csv | Open |
| Bahamas Run registration path is not yet defined | MER-EVT-001, MER-TRK-103 | Open |
| Dashboard and reporting .md files had messy nested formatting from initial setup | Multiple .md files | Resolved 2026-06-03 |
| Duplicate Bluff House Bahamas Run project/campaign/task records created scope confusion | BH-EVT-001 / BH-EVT tasks / BH-EVT campaign row | Resolved 2026-06-03 — removed from active trackers; old Bluff House markdown file marked removed from active tracking |

---

## Recommended Maintenance Rule

After major project updates, AI should:

1. Re-read all updated files to confirm changes were saved correctly.
2. Run a data quality check against the checklist above.
3. Summarize any missing data, inconsistent links, or failed updates.
4. Flag any new issues in this file.
5. Refresh dashboard.md, current-priorities.md, leadership-review.md, and weekly-summary.md when relevant data has changed.

---

## Corporate Scope Checks

Corporate-wide projects should use Marina ID CORP. Portfolio-wide tracking issues should link to CORP-TRK-001. Corporate projects should have Markdown files under marinas/corporate/projects/. Dashboard files should include Corporate / All Marinas when active CORP projects exist. Tracking issues affecting all marinas should reference CORP as Marina unless marina-specific.

---

## Corporate Current Flags

| Flag | File / Location | Status |
|---|---|---|
| Corporate projects not using Marina ID CORP | project-index.csv, marina-index.csv | Open |
| Portfolio-wide tracking issues not linked to CORP-TRK-001 | tracking-issues.csv | Open |
| Need to confirm final list of all 15 marinas for marina-index.csv | marina-index.csv | Open |
| Need to determine if any existing projects should move to Corporate / All Marinas | project-index.csv | Open |
