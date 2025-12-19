# CoreX AI Tickets System

---

## Overview

**CoreX AI Tickets** is an advanced ticket management system enhanced with an AI assistant. It automates first responses, assists users inside tickets, and escalates to staff only when necessary, reducing workload while keeping support efficient and controlled.

The system is fully integrated with Discord and managed through an interactive configuration panel.

---

## Key Features

### 🎫 AI-Powered Ticket Assistance
- AI greets users when a ticket is opened
- Automatically answers common questions
- Escalates to staff when required

### 🚨 Smart Report Flow
- Report system with **confirm / cancel** step
- Prevents accidental or false staff alerts

### 🧭 Ticket Controls
Available directly inside tickets:
- **Claim** — assign a ticket to a staff member
- **Transcript** — export ticket history
- **Escalate** — notify support roles
- **Close** — close the ticket safely

---

## AI Training System

CoreX AI can be trained and managed using dedicated commands:

```bash
/ai train
/ai memory view
/ai memory delete
/ai memory export
/ai reset
```

---

## Training Features
- Server-specific AI Memory
- Role-restricted training access
- Full memory reset option
- Exportable AI data

---

## Configuration Panel

All major settings are managed through the **config panel.**

### Available Controls:
- **Support Roles** — roles notified on escalation
- **Manager Roles** — higher-level control access
- **Train Role** — who can train the AI
- **Reset AI** — wipe all AI notes and data
- **Panel Channel Picker** — select where the ticket panel is posted
- **Guide Button** — in-panel help and instructions

All changes apply instantly.

---

## Requirements
Permissions:
- **User:** Manage Server (for setup and configuration)
- **Bot:** Administrator (recommended)
Roles:
- Support Role
- Manager Role
- Train Role (for AI training)

---

## Notes
- The AI operates only within ticket channels.
- Escalation automatically pings configured support roles.
- Transcripts can be exported with optional channel selection.
