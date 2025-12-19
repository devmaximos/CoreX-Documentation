# LOA & RDQ Request System

---

## Overview

The **LOA (Leave of Absence)** and **RDQ (Reduced Duty Quota)** system allows members to formally request time off or reduced activity through Discord slash commands.
All requests are handled privately via DMs and reviewed by staff in a designated review channel.

The system is fully automated, persistent, and designed to minimize manual moderation effort.

⚠️ **Important Requirement**
The LOA & RDQ system must be enabled and configured from the config panel for requests and reviews to function.

---

## Command Usage

### Member Commands (DM-based)
```bash
/reqloa
/reqrdq
```
These commands:
- Can only be used by members
- Automatically move the request flow to DMs
- Guide the user through the request process step by step

### Staff / Reviewer Commands
```bash
/loa_active
/rdq_active
/loa_forceoff
/rdq_forceoff
```

Purpose:
- View currently active LOA / RDQ entries
- Manually remove or override active requests if required

---

## How to Enable the System
1. Run the `/config` command.
2. Open the **LOA / Reduced Quota** configuration section.
3. Enable the system.

Set:
- Review channel
- Reviewer roles
- LOA role
- RDQ role
- Auto-removal settings (optional)

Once enabled, the system is active immediately.

---

## Request Flow (User Side)
1. User runs `/reqloa` or `/reqrdq`.
2. Bot opens a **DM-based form**.
3. User submits required information (reason, duration, etc.).
4. Request is sent to the configured review channel.
5. User is notified that their request is pending review.

---

## Review Flow (Staff Side)

### Requests appear in the review channel with:
- Request details
- User information
- Accept / Deny buttons

### On Acceptance
- The appropriate role (LOA or RDQ) is assigned automatically.
- Optional expiry timer starts (if enabled).
- User receives a confirmation DM.

### On Denial
- No role is assigned.
- User is notified via DM with the decision.

---

## Automatic Role Management
- LOA / RDQ roles are assigned immediately upon approval.
- If expiry is enabled:
    - Roles are automatically removed when the duration ends.
- Manual removal is possible at any time via force-off commands.

---

## Requirements

Permissions
- **User:**
    - Ability to use slash commands
    - Open DMs with the bot

- **Staff:**
    - Access the configured review channel
    - Assigned reviewer role

- **Bot:**
    - Manage Roles
    - Send Messages
    - Read Message History

---

## Notes
- Requests are always handled privately via DMs.
- Staff actions are restricted to reviewer roles.
- Disabling the system immediately stops new requests.
- Existing active LOA / RDQ entries remain stored unless manually removed.
