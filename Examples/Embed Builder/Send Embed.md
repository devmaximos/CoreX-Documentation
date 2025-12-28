# Embed Builder System: Send Embed

---

## Overview

The **Send Embed** system allows administrators to post previously saved custom embeds to any channel within the server. This is ideal for deploying pre-configured rules, information cards, or styled announcements that have been designed using the Embed Builder.

⚠️ **Important Requirement** The **Embed Builder** feature **must be enabled from the config panel** for this system to work. If it is disabled, you will not be able to send or manage saved embeds.

---

# Command Usage

```bash
/send_embed embed_id:[id] channel:[target_channel]
```

# How to Send a Saved Embed
1. Identify the **ID** of the embed you wish to send. If you are unsure of the ID, use the `/embed_list` command to view all saved designs and their corresponding IDs.
2. Run the `/send_embed` command.
3. Enter the **embed_id** (e.g., `1`).
4. Select the **target channel** where the embed should be posted (optional; defaults to current channel if not specified).
5. Press **Enter** to execute.

The bot will display a "Sending command..." status before confirming that the embed was successfully sent to the target location.

---

# What the System Does
- **Retrieves Saved Data:** Pulls the full configuration (titles, fields, images, and buttons) associated with the provided ID.
- **Multi-Channel Deployment:** Allows you to send the same saved embed to multiple channels without rebuilding it.
- **Interactive Elements:** Automatically includes any URL buttons or interactive components originally saved with the embed.
- **Execution Confirmation:** Provides a private confirmation message to the moderator, including a direct link to the sent embed.

---

# Requirements
Permissions:
- **User:** Must have permission to manage server configuration or messages (Admin recommended).
- **Bot:** View Channels, Send Messages, Embed Links.

Configuration:
- **Embed Builder** must be **Enabled** in the `/config` Plugins section.

---

# Notes
- **Retrieving IDs:** If you forget your embed IDs, always use `/embed_list` to get a complete overview of your saved content.
- **Live Edits:** If you update an embed using the builder, you will need to resend it using `/send_embed` to display the updated version in your public channels.
- **ID Precision:** Ensure you enter the exact ID from your list to avoid sending the wrong content.
