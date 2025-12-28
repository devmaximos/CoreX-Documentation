
# Create Embed

---

## Overview

The **Embed Builder** system allows administrators to design and save highly customized, professional-looking messages (embeds). These can include specific titles, descriptions, colors, images, and interactive url buttons, making them perfect for rules, information channels, or announcements.

⚠️ **Important Requirement** The **Embed Builder** feature **must be enabled from the config panel** for this command to work. If it is disabled, you will not be able to access the builder interface.

---

# Command Usage

```bash
/create_embed name:[embed name]
```

# How to Build an Embed
1. Run the `/create_embed` command and provide a unique **name** (ID) for your embed to save it.
2. Fill out the initial **Create Embed** form including Title, Description, Color, and Footer, then click **Submit**.
3. Use the interactive buttons to further customize your embed:
    * **Set Thumbnail:** Add a small image to the top-right.
    * **Set Banner Image:** Add a large image to the bottom of the embed.
    * **Add Field:** Add organized "Field names" and "Values" with optional inline formatting.
    * **Add URL Button:** Attach a button that links to an external website.
    * **Set Branding:** Customize author or footer details.
4. Click **Save Embed** to finalize your creation.

---

# What the System Does
- **Interactive Interface:** Provides a real-time preview of your embed as you build it.
- **Saves to Database:** Stores your custom design under a unique ID for later use.
- **Button Support:** Allows for the addition of multiple URL buttons with custom labels.
- **Dynamic Formatting:** Supports standard Markdown and custom field organization.

---

# Requirements
Permissions:
- **User:** Must have permission to manage server configuration (Admin recommended).
- **Bot:** View Channels, Send Messages, Embed Links, Manage Messages.

Configuration:
- **Embed Builder** must be **Enabled** in the `/config` Plugins section.

---

# Notes
- **Embed ID:** Remember the name you give your embed; you will need it to send or edit the embed later.
- **URLs:** All button links must start with `http://` or `https://`.
- **Cleanup:** You can use "Clear Components" or "Clear Fields" if you need to start over on specific sections.
