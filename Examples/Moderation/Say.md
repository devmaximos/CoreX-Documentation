# Utility System: Say Command

---

## Overview

The **Say Command** allows authorized users to send messages through the bot to a designated channel. This is useful for making official announcements, posting formatted content, or communicating as the bot to maintain a professional server appearance.

Each time the command is used, the bot provides a confirmation of the sent message and logs the action for staff oversight.

---

# Command Usage
```bash
/say channel:[target_channel] message:[text]
```

# How to Send a Message as the Bot
1. Type `/say` in any channel where you have the required permissions.
2. Select the **target channel** where the message should be posted.
3. Type the **message** content you want the bot to send.
4. Press **Enter** to execute.

The bot will display a "Sending command..." status before confirming that the message was successfully sent to the target location.

---

# What the System Does
- **Channel Routing:** Delivers your message to any channel you specify, regardless of where the command was initiated.
- **Bot Identity:** The message appears as if sent directly by the CoreX bot.
- **Execution Tracking:** Provides an immediate "Sent Message" confirmation embed containing the destination link.
- **Staff Accountability:** Records the executor’s name and the message destination to prevent misuse.

---

# Requirements
Permissions:
- **User:** Must have permission to manage messages or server configuration.
- **Bot:** View Channels, Send Messages, Embed Links.

---

# Notes
- **Channel Selection:** You can select the target channel from a dropdown list or by typing the channel name.
- **Confirmation:** The "Sent Message" confirmation is only visible to the user who ran the command, keeping the public interaction clean.