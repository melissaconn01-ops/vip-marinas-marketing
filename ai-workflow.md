# AI Workflow Guide

## Purpose

This document explains how ChatGPT, Codex, and GitHub work together for VIP Marinas project management.

The goal is to preserve important decisions, project context, tasks, and operational knowledge so work can continue across conversations, devices, and AI sessions.

---

## The Three-Layer Workflow

### Layer 1 — Chat / Working Session

Use ChatGPT chats for:

- Brainstorming
- Research
- Strategy discussions
- Drafting emails and documents
- Exploring options
- Reviewing problems
- Making decisions

Not every thought needs to become a GitHub record.

---

### Layer 2 — Chat Intake Log

Use `chat-intake-log.md` for:

- Important decisions
- New project ideas
- Status changes
- Meeting notes
- Vendor information
- Tasks discovered during conversations
- Context that another chat may need later

This prevents important information from being trapped in one conversation.

---

### Layer 3 — Official Repository Records

Confirmed information moves into:

- `project-index.csv` — project-level status
- `project-tasks.csv` — action items and ownership
- `campaign-tracker.csv` — campaigns
- `tracking-issues.csv` — measurement/data issues
- `event-tracker.csv` — events
- Marina project markdown files — background, decisions, and context
- Dashboard/reporting files — leadership visibility

These files are the official source of truth.

---

## Update Process

### For Quick Capture

Say:

> Add this to the intake log.

The information should be added to `chat-intake-log.md`.

### For Official Updates

Say:

> Update the repo from this.

AI should:

1. Read relevant files.
2. Identify required changes.
3. Propose updates.
4. Receive approval unless auto-commit was explicitly requested.
5. Commit changes.
6. Re-open files and verify updates.

---

## Cross-Device / Cross-Chat Expectations

GitHub acts as the shared project memory layer.

It does not replace ChatGPT chat history. A new chat should use the repository as the project reference rather than assuming it can see every previous conversation.

When starting a new project conversation:

1. Connect to/read the repository.
2. Review the relevant project files.
3. Continue from the current source of truth.

---

## File Management Rules

- Do not paste full chat transcripts into GitHub unless needed.
- Summarize decisions and outcomes.
- Keep structured trackers clean.
- Use markdown files for context that does not fit into spreadsheets.
- Use intake for temporary information before cleanup.

---

## Default Approval Rule

Default: Approval Before Commit.

AI must propose changes before committing structured repository updates unless the user explicitly requests auto-commit.
