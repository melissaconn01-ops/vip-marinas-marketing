# VIP Marinas Marketing — Project Management Repository

## Purpose

This repository is the source of truth for VIP Marinas marketing project management. It keeps projects, tasks, campaigns, tracking issues, decisions, and leadership follow-up organized so work can continue across conversations, devices, and AI sessions.

## Core Workflow

The system follows this hierarchy:

**Marina → Project Topic → Managed Task / Item**

- Marina folders contain property-specific context and projects.
- CSV trackers contain structured operational data.
- Markdown files contain project background, decisions, notes, and context.
- Dashboard files provide human-readable reporting layers.

---

## AI Workflow

Use these layers together:

### 1. Chat / Working Session

Use ChatGPT or Codex sessions for:

- Brainstorming
- Research
- Strategy
- Drafting
- Problem solving
- Decision making

Not every conversation needs to become a repository update.

### 2. Chat Intake Log

Use `chat-intake-log.md` for important information that needs to be preserved but has not yet been organized into official trackers.

Examples:

- Meeting notes
- New ideas
- Vendor updates
- Decisions made in chat
- Project changes discovered during discussion

### 3. Official Project Records

Move confirmed information into:

- `project-index.csv`
- `project-tasks.csv`
- `campaign-tracker.csv`
- `tracking-issues.csv`
- `event-tracker.csv`
- Marina project markdown files
- Dashboard/reporting files

See `ai-workflow.md` for the full process.

---

## Root-Level Files

| File | Purpose |
|---|---|
| `README.md` | Repository guide and operating rules |
| `ai-workflow.md` | AI + GitHub workflow instructions |
| `chat-intake-log.md` | Fast capture from chats and working sessions |
| `project-index.csv` | Major projects by marina |
| `project-tasks.csv` | Tasks, approvals, blockers, next steps |
| `campaign-tracker.csv` | Marketing campaigns |
| `tracking-issues.csv` | Tracking, CRM, GA4, Ads, phone, form, and lead issues |
| `event-tracker.csv` | Event-specific planning and tracking |

---

## Source of Truth Rules

- CSV files are the structured source of truth.
- Markdown files store context, decisions, and project details.
- Dashboards summarize tracker data.
- Chat intake captures information before it is processed.

---

## AI Editing Rules

### Read Before Write

AI must read relevant files before making changes.

### Approval Before Commit

Default workflow:

1. AI reads relevant files.
2. AI proposes updates.
3. User approves.
4. AI commits changes.

Auto-commit is only allowed when explicitly requested.

### Read After Write

After updates, AI verifies that the correct files, rows, or sections were changed.

### Failed Update Reporting

If an update fails or is blocked, AI must report it in a "Failed or Skipped Updates" section.

---

## Cross-Property Projects

Use Related Project ID only when separate project ownership or responsibilities truly exist.

Do not create duplicate projects simply because multiple properties are involved.

Example:

A Meridian event hosted at Bluff House remains a Meridian project unless Bluff House has separate owned responsibilities requiring its own project record.

---

## Reporting Files

| File | Purpose |
|---|---|
| `dashboard.md` | Portfolio dashboard |
| `current-priorities.md` | Current priority work |
| `leadership-review.md` | Leadership decisions and approvals |
| `weekly-summary.md` | Weekly progress summary |

---

## Status Standards

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
