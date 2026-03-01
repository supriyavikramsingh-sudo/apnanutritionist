---
summary: "Tool configuration for ApnaNutritionist"
---

# TOOLS.md — ApnaNutritionist Tool Notes

## gog (Google Workspace CLI)
- Binary: ~/.local/bin/gog (v0.9.0)
- Account: supriyavikramsingh@gmail.com
- Permissions: Google Drive + Google Sheets
- Use for: creating user sheets, sharing with 
  readers, appending meal log rows

## Telegram
- Bot: @apnanutritionist_bot
- dmPolicy: open
- allowFrom: ["*"]
- Session scope: per-channel-peer

## Models
- Photo meal logging: openai/gpt-5
- Everything else: openai/gpt-5-mini