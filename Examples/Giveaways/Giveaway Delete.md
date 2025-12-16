# /giveaway_delete Command Documentation

---

## Overview

The `/giveaway_delete` command allows authorized users to delete an active giveaway from a Discord server. The giveaway will be removed immediately, and participants will no longer be able to enter it.

Key Features:
- Delete any active giveaway quickly.
- Requires only the giveaway message ID or link.
- Automatic winner selection and announcement
Permissions:
- **User:** Must have permission to manage giveaways (usually Admin/Moderators).
- **Bot:** Must have `Manage Messages` permission in the channel containing the giveaway.

---

## Command Syntax

```bash
/giveaway_delete message:<string>

```

---

## Arguments

| Argument | Type | Description | Example |
|----------|------|-------------|---------|
| `message` | string | The giveaway message ID or the full message link to delete the giveaway. | `123456789012345678` or `https://discord.com/channels/12345678912345678/12345678912345678/12345678912345678 |

