# Server Stats Delete

---

## Overview

The Server Stats Delete action removes all Server Stats channels from the server and disables their updates. This is useful when you no longer want to display live server statistics or wish to reset the Server Stats setup.

⚠️ **Important:**  
Server Stats must be enabled in the config panel for this action to be available.


# Requirements
Permissions:
- **User:** Must have permission to manage server configuration (usually Admin/Moderators)
- **Bot:** Manage Channels

---

## Command Usage

```bash
/serverstats_delete
```

---

# What This Does
- Deletes all existing Server Stats channels
- Stops all automatic stat updates
- Resets the Server Stats configuration

# Notes
- This action is irreversible and cannot be undone.
- Server Stats can be re-enabled by using the `/serverstats setup` command
