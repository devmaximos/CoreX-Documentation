# Counting System

---

## Overview

The **Counting System** introduces a fun, interactive mini-game to your server where members work together to count as high as they can. The system automatically tracks the current number, validates entries, and manages streaks. If someone breaks the sequence or counts twice in a row, the counter resets, making every number count!

⚠️ **Important Requirement** The **Counting System** must be **Enabled** from the config panel. You must also designate a **Counting Channel** for the bot to begin monitoring numbers.

---

# Configuration Guide

To set up the system as shown in the dashboard:
1. Run `/config` and navigate to **Plugins** -> **Counting**.
2. **Select Counting Channel:** The primary channel where the game takes place.
3. **Select Revive Channel (Staff only):** A private channel where staff can monitor and use the revive command.
4. **Select Log Channel (Optional):** A channel to track every count and reset for record-keeping.
5. **Set Roles:** (Optional) Define an **Allowed Role** to participate or a **Blacklist Role** to restrict specific users.
6. **Reset Counting State:** Use this button in the config menu if you need to manually wipe the current progress and start from zero.

---

## Key Features

- **Auto-Validation:** The bot automatically reacts with a ✅ for correct numbers and a ❌ for incorrect ones.
- **Fail-Safe Reset:** If a user types the wrong number or ruins the streak, the bot reacts with ❌ and resets the count to 1.
Role Control:** Fine-tune your community engagement by restricting who can count via specific Discord roles.
- **Revive System:** If a high streak is lost to a troll or a mistake, staff can instantly restore the previous count using the revive command.
- **Real-time Logging:** Track every move in your log channels to ensure fair play.

---

## Requirements
Permissions:
- **User:** Must have the allowed role (if set) and not have the blacklist role (if set).
- **Staff:** Must have Administrator or designated Moderator roles to access config and revive tools

Configuration:
- **Counting plugin** must be **Enabled** in the `/config` command
- **Counting Channel** must be correctly assigned for the bot to "listen" to numbers.

--- 

## Notes
- **No Double Counting:** The same user cannot count two numbers in a row; a different person must provide the next number.
