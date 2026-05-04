# Awesome OpenCode Config

This repository contains OpenCode configuration assets meant to live under your
global OpenCode config directory.

## Install to `~/.config/opencode`

1. Create the target folders:
   - `~/.config/opencode/`
   - `~/.config/opencode/agents/`
   - `~/.config/opencode/skills/`
2. Copy the files from this repo:
   - `opencode.json` → `~/.config/opencode/opencode.json`
   - `agents/*` (from this repo's `agent/` directory) → `~/.config/opencode/agents/`
   - `skills/*` → `~/.config/opencode/skills/`

`opencode.json` points to `./skills`, so keeping the skills folder inside
`~/.config/opencode/` is required for the paths to resolve.

If you already have an `opencode.json`, merge the `plugin`, `mcp`, and `skills`
sections instead of overwriting your existing settings.
