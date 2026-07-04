# EweTube Config

Public remote configuration for Ewe File Manager. App source is in the private `TrueIntelligence/EweTube` repo.

| File | Purpose |
|------|---------|
| `config.json` | Feature flags (`reviewMode`, download UI, etc.). Bump `version` when changed. |
| `voice-commands.json` | Voice control phrases (English + Arabic). Bump `version` when changed. |

The iOS app fetches these on launch via `raw.githubusercontent.com`.
