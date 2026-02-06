# Leveling System

---

## Overview

The **Leveling System** incentivizes server activity by rewarding users with Experience Points (XP) for every message sent. As users gain XP, they level up, allowing you to track your most active members and celebrate their progress with customizable announcements.

⚠️ **Important Requirement** The **Leveling Plugin** must be **Enabled** from the `/config` panel. You should also set up a **Level Log Channel** to announce when a user reaches a new milestone.

---

# Configuration Guide

To customize your leveling experience:
1. Run `/config` and navigate to **Plugins** -> **Leveling**.
2. **Edit XP Range:** Set the minimum and maximum XP a user can earn per message (e.g., 5-15 XP).
3. **Edit Level-Up Message:** Customize the text that appears when a user levels up. You can use placeholders like `{user}` and `{level}` to make it dynamic.
4. **Level Log Channel:** Select the channel where level-up announcements will be posted.
5. **Set Level-up Log Channel (Optional):** A secondary logging option for staff to track progression behind the scenes.

---

# Command Usage

### For Users
```bash
/level member:[optional_user]
```
Displays a personalized Rank Card showing current Level, Total XP, Server Rank, and a progress bar to the next level.

```bash
/leaderboard limit:[optional_number]
```
Displays the top active members in the server based on their XP and Level.

---

## Key Features

- **Dynamic XP:** Prevent "XP farming" by setting a randomized range for every message sent.
- **Custom Rank Cards:** Beautifully designed embeds that show user progress, rank position, and total XP at a glance.
- **Milestone Announcements:** Automatically notify the server (or a specific channel) whenever a user reaches a new level.
- **Leaderboards:** Foster healthy competition with a server-wide ranking system.
- **Template Support:** Full control over how level-up messages are phrased, allowing for unique server branding.

---

## Requirements
Permissions:
- **Staff:** Administrator or moderator permissions to access the `/config` dashboard

Configuration:
- **Leveling Plugin** must be enabled in the `/config` panel
- **Log channel** should be set to ensure level up messages are visible. ( optional )

--

## Notes
- **Cooldowns:** The system typically includes an internal cooldown to ensure users don't spam messages just to gain XP.
- **Placeholders:** Ensure you include {level} in your message template so users know exactly what rank they have achieved!
