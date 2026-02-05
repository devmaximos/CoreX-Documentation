# Suggestions System

---

## Overview

The **Suggestions System** provides a streamlined way for community members to submit ideas and feedback. Each suggestion is posted as an organized embed with interactive voting buttons, allowing administrators to gauge community interest and officially manage the status of each proposal.

⚠️ **Important Requirement** The **Suggestions Plugin** must be **Enabled** from the config panel. You must also designate a **Suggestions Channel** before the system can process new entries.

---

# Command Usage

### For Users
```bash
/suggest create suggestion:[text] anonymous:[Show my name/Anonymous] image:[Image Upload]
```

### For Administrators
```bash
/suggest accept id:[suggestion_id]
/suggest deny id:[suggestion_id]
```

### Key Features
- **Voting System:** Automatically attaches Upvote and Downvote buttons to every suggestion to track community sentiment.
- **Anonymous Submissions:** Allows users to submit feedback privately if the server configuration permits.
- **Auto-Threading:** Optionally creates a dedicated thread for every suggestion to keep discussions organized and out of the main channel.
- **Status Management:** Staff can update suggestions to "Accepted" or "Denied," which updates the embed color and notifies the community of the decision.

---

### Requirements
Permissions:
- **User:** Must have the specific role defined in the config ( Default: @everyone )
- **Staff:** Must have the designated Management/Admin role to use accept/deny commands

Configuration:
- **Suggestion Plugin** must be **Enabled** in the `/config` command
- **Target Channel** must be set for suggestions to appear.

---

### Notes
- **Suggestion ID:** Every suggestion is assigned a unique ID found in the footer of the message. Staff need this ID to perform management actions.
- **Decision Comments:** When accepting or denying, the provided "reason" will be displayed on the updated embed for transparency.
- **Thread Control:** If "Auto Thread" is enabled, members can discuss the suggestion without cluttering the main channel.
