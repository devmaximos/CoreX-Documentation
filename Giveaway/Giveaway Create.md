# `/giveaway_create` Command Documentation

---

## Overview

The `/giveaway_create` command allows server moderators or authorized users to start a giveaway in a Discord server. Participants can enter by reacting to the giveaway message, and the bot will automatically pick winners once the giveaway ends.

Key Features:
- Customizable duration, prize, number of winners, and ping options.
- Optional target channel or thread
- Automatic winner selection and announcement
Permissions:
- **User:** Must have the permission to manage giveaways (usually Admin/Moderators)
- **Bot:** Send Messages, Add Reactions, Manage Messages in the target channel.

---

## Command Syntax

```bash
/giveaway_create duration:<duration> prize:<string> winners:<integer> ping:<string|optional> channel:<channel|optional>

```

---

## Arguments

| Argument | Type | Description | Example |
|----------|------|-------------|---------|
| `duration` | string | The length of time the giveaway runs. Supports `d` (days), `h` (hours), `m` (minutes). | `1h30m`, `45m`, `2d` |
| `prize` | string | The prize that participants will compete for. | `"Discord Nitro"` |
| `winners` | integer | Number of winners to select. | `1`, `3` |
| `ping` | string (optional) | Optional text to ping participants. Can be `@everyone`, `@here`, or a role mention. | `@everyone` |
| `channel` | channel (optional) | Target text channel or thread to host the giveaway. If omitted, defaults to the current channel.

