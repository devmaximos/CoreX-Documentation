# Embed Management - Embed List

---

## Overview

The **Embed Management** system provides a centralized way to view, organize, and modify all custom embeds created on the server. Using the list command, administrators can keep track of their saved designs and perform essential maintenance tasks like renaming or deleting existing embeds.

⚠️ **Important Requirement** The **Embed Builder** feature **must be enabled from the config panel** for management commands to function.

---

# Command Usage

```bash
/embed_list
```

# How to Manage Saved Embeds
1. Run the `/embed_list` command in any channel.
2. Review the list of saved embeds to find the specific **ID** or **Name** you need.
3. Use the **Choose an embed to manage** dropdown menu to select a specific entry.
4. Select one of the following actions:
    * **Rename Selected:** Change the internal name/ID of the selected embed for better organization.
    * **Delete Selected:** Permanently remove the selected embed from the bot's database.

---

# What the System Does
- **Inventory Overview:** Displays all saved embeds, including their assigned IDs and the number of interactive buttons attached to each.
- **Dynamic Renaming:** Allows for instant updates to embed IDs without needing to recreate the content.
- **Database Cleanup:** Provides a secure way to delete old or redundant embeds.
- **Staff Interface:** Uses intuitive Discord components (dropdowns and buttons) for a seamless management experience.

---

# Requirements
Permissions:
- **User:** Must have permission to manage server configuration (Admin recommended).
- **Bot:** View Channels, Send Messages, Embed Links, Manage Messages.

Configuration:
- **Embed Builder** must be **Enabled** in the `/config` Plugins section.

---

# Notes
- **ID Retrieval:** The `/embed_list` command is the primary method for finding the IDs required for the `/send_embed` command.
- **Permanent Deletion:** Once an embed is deleted through this menu, it cannot be recovered.
- **Real-time Sync:** Any changes made to the names or list are updated instantly across the bot's database.
