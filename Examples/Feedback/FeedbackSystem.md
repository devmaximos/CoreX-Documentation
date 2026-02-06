# Feedback System

---

## Overview

The **Feedback System** allows community members to rate their interactions with staff members. By providing a star rating (1-5) and optional comments, users help maintain high standards of service, while administrators can track performance through detailed feedback summaries.

⚠️ **Important Requirement** The **Feedback System** must be **Enabled** from the `/config` panel. You must also select a **Feedback Channel** where the reports will be sent for review.

---

# Configuration Guide

To set up the system as shown in the video:
1. Run `/config` and navigate to **Plugins** -> **Feedback**.
2. **Select Feedback Channel:** Choose the channel where new feedback reports will be posted.
3. **Select Staff Roles:** Define which roles are considered "Staff" and can receive feedback.
4. **Void Roles:** (Optional) Select roles that are ignored by the system (e.g., specific bots or trial roles).
5. **Toggle Staff Mention:** Enable this if you want the staff member to be pinged when they receive new feedback.
6. Click **Save Settings** to finalize.

---

# Command Usage

### For Users
```bash
/feedback_rate member:[user] rating:[1-5] comment:[optional_text]
```
*Submits a rating for a specific staff member. The result is sent to the configured feedback log.*

### For Staff/Admins
```bash
/feedback_view member:[user]
```
*Displays a detailed summary for a staff member, including their Average Rating, Total Ratings, a star distribution chart (1-5), and a list of recent comments.*

```bash
/feedback_void member:[user]
```
*Clears or voids feedback for a specific member if needed (Admin only).*

---

# Key Features
- **Star Rating System:** A simple 1-5 scale makes it easy for users to provide quick, quantitative feedback.
- **Performance Analytics:** The `/feedback_view` command provides a visual breakdown of how a staff member is performing over time.
- **Transparency:** Optional comments allow users to explain their ratings, giving context to the data.
- **Staff Notifications:** Keep your team in the loop by automatically mentioning them when they receive feedback.
- **Admin Oversight:** Easily manage and review all feedback from a centralized channel.

---

# Requirements
Permissions:
- **Staff:** Must have one of the roles selected in the Feedback config to be eligible for ratings.

Configuration:
- **Feedback Plugin** must be **Enabled** in the `/config` panel.
- **Staff Roles** must be assigned in the config, otherwise the bot won't know who can be rated.

---

# Notes
- **Rating Limits:** Users are encouraged to provide honest feedback; ensure your staff roles are correctly updated to avoid "rating" non-staff members.
- **Average Calculation:** The bot automatically calculates the mean score to show the average in the summary embed.
