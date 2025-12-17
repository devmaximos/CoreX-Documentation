# Welcome System Configuration

---

## Overview

The Welcome System allows server administrators to customize welcome and leave messages, define where they are sent, and automate basic onboarding actions. It helps new members feel welcome while keeping staff informed about joins and leaves.

Key Features:
- Custom welcome and leave messages
- Dynamic placeholders support
- Configurable welcome and log channels
- Optional auto-role on join
- Optional auto-delete for welcome messages

Permissions:
- **User:** Must have permission to manage server configuration (usually Admin/Moderators)
- **Bot:** Send Messages, Manage Messages, Manage Roles (for auto-role)

---

## Placeholders

The following placeholders can be used in welcome and leave messages:

- `{user}` → The joining or leaving user  
- `{membercount}` → Current server member count  
- `{guild}` → Server name  

---

## Welcome Message

Defines the message sent when a new member joins the server.

Example:
```bash
Welcome {user} to {guild}! You're member #{membercount}.
```

---

## Leave Message

Defines the message sent when a member leaves the server.

Example:
```bash
{user} left {guild}.
```

---


---

## Configuration Options

| Setting | Description |
|--------|-------------|
| **Welcome Channel** | The channel where welcome messages are sent |
| **Log Channel** | Optional channel for join/leave logs |
| **Auto Role** | Optional role automatically granted to new members |
| **Auto-delete Welcome** | Automatically deletes welcome messages after a set delay or never |

---

## Controls

The Welcome System is managed through interactive buttons and selectors:

- **Edit Welcome Message** — Update the welcome message content  
- **Edit Leave Message** — Update the leave message content  
- **Set Auto-delete** — Configure automatic deletion timing  
- **Set Welcome Channel** — Choose where welcome messages are sent  
- **Set Log Channel** — Choose where join/leave logs are sent  
- **Set Auto Role** — Select a role to grant on join  

---

## Notes

- All settings are saved per server.
- Changes apply immediately after configuration.
- If no welcome channel is set, welcome messages will not be sent.

---
