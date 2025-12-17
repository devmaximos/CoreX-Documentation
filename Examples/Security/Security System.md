# Security System Configuration

---

## Overview

The Security System protects the server from destructive or abusive actions by monitoring sensitive events in real time. It operates silently in the background and automatically enforces protection rules when limits are exceeded.

⚠️ **Important Requirement**  
The Security System **must be enabled from the config panel** for any protection to work.

---

## Command Usage

```bash
/config
```

---

# How to enable Security
1. Run the `/config` command.
2. Open the **Security** option and enable it.
3. Configure whitelist and protection settings.

Once enabled, the system becomes active immediately

---

# What the Security System Does
- Monitors sensitive server actions continuously.
- Detects actions such as mass ban, deletions, spam and mentions
- Identifies the executor using Audit Logs
- Automatically enforces punishments if limits are exceeded
- Ignores actions performed by whitelisted users.

The system does not send public messages and works silently.

---

# Whitelist Requirement
Trusted users or roles **must be whitelisted** to prevent accidental punishment.'
Whitelisted options available in the config panel:
- Whitelist by role
- Whitelist by user ID

Whitelisted entities are never restricted by the Security System.

---

# Requirements
Permissions:
    - **User:** Must have permission to manage server configuration (usually Admin)
    - **Bot:** Administrator, View Audit Log
Configuration:
    - Security system enabled via `/config`

---

# Notes
- Disabling Security System immediately stops all protections.
- Punishments are logged only via Discord Audit Logs.
- Configuration changes apply instantly.
