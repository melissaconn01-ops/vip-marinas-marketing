# Chat Intake Log

**Purpose:** Fast capture for useful updates from any ChatGPT chat, mobile conversation, desktop app session, Codex work session, meeting note, vendor conversation, or planning thread before the information is cleaned up into the official trackers.

This file is not the final source of truth for structured project status. It is the holding area that prevents important context from getting lost between chats.

Official source-of-truth files remain:

- `project-index.csv`
- `project-tasks.csv`
- `campaign-tracker.csv`
- `tracking-issues.csv`
- `event-tracker.csv`
- Marina-specific project markdown files
- Dashboard/reporting files after refresh

---

## Intake Rules

1. Add entries here when a chat produces a meaningful project update but the update has not yet been sorted into the official trackers.
2. Keep entries concise. Do not paste full raw transcripts unless specifically needed.
3. Use the standard intake format below so another chat, Codex, or future AI session can process the update.
4. Mark `Needs repo update` as `Yes` when the update should become an official tracker/project-file change.
5. After an entry is processed into the official repo files, update the intake entry status to `Processed` or add a short processing note.

---

## Standard Intake Format

```md
## Intake Entry — YYYY-MM-DD — Short Topic

**Status:** New / Reviewed / Processed / No Action Needed
**Source Chat / Topic:**
**Marina:**
**Project:**
**Project Topic:**
**What changed:**
**New tasks:**
**Completed tasks:**
**Blockers:**
**Approvals needed:**
**Tracking implications:**
**Next step:**
**Needs repo update:** Yes / No
**Processing note:**
```

---

## Intake Entries

_Add new entries below this line._

---

## Intake Entry — 2026-08-03 — Chat-to-GitHub Workflow

**Status:** Processed  
**Source Chat / Topic:** VIP Marinas GitHub Project Management Assistant setup  
**Marina:** CORP / All Marinas  
**Project:** GitHub Project Management System  
**Project Topic:** Project Management / AI Workflow  
**What changed:** Created a flow where important updates from any chat can be captured in GitHub before being sorted into official project trackers.  
**New tasks:** Use this log for fast capture from future chats; review intake periodically and move confirmed items into structured files.  
**Completed tasks:** Created initial intake structure.  
**Blockers:** None.  
**Approvals needed:** None for this intake structure.  
**Tracking implications:** This improves cross-chat continuity but does not automatically sync full ChatGPT chat history across all devices or Codex.  
**Next step:** Use `ai-workflow.md` and this intake log as the standard handoff process.  
**Needs repo update:** No  
**Processing note:** Initial workflow setup completed.
