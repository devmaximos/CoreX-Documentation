# Server Stats System

---

## Overview

The Server Stats system displays live server statistics using automatically updating channels. These channels reflect real-time server data such as member counts and update without manual interaction.

⚠️ **Important Requirement**  
The Server Stats feature **must be enabled from the config panel** for this system to work.  
If it is disabled, you won't be able to setup this feature.

Key Features:
- Live updating server statistics
- Automatic updates without manual interaction
- Customizable stat channels


---

# Command Usage 

```bash
/serverstats setup
```

# How to Enable Server Stats
1. Run the `/config` command
2. Navigate to the 'Server Stats' section and select it.
3. Run `/serverstats setup` and once ready, the bot will begin managing and updating stat channels automatically.

---

# What the System Does
- Creates or manages dedicated stat channels.
- Updates channel names dynamically as server data changes.
- Keeps statistics accurate without manual refresh.

---

# Requirements
Permissions:
- **User:** Must have permission to manage server configuration (usually Admin/Moderators)
- **Bot:** Manage Channels, View Channels
Configuration:
- Server Stats must be **enabled** in the config panel
- The bot must be allowed to create and rename channels
