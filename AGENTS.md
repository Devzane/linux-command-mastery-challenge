# AGENTS.md

Docs-only repo: a 30-day Linux challenge. No build, test, lint, CI, or package manager.

## Structure

- `day-NN-<slug>/`: one folder per day. Each holds `README.md` (summary + surprise), `commands.md` (10 commands, syntax + own-words explanation), `drill.md` (task + exact commands run in order), `evidence/` (screenshot/transcript; currently just `.gitkeep`).
- `day-30-capstone/` additionally holds `health-check.sh` (stub; capstone SSH-deploy + verify script).
- `journal/command-journal.md`: running log of all 300 commands (10/day), one row per command.
- `README.md` (root): source of truth for progress table, six phases, capability map. Update it when completing a day.
- Checkpoints/synthesis days: 5, 10, 15, 20, 25, 30 (`*-checkpoint/`, plus capstone).

## Working standards (from root README — enforce these)

- One commit per day, message `Day N: <topic>`. Never batch days or backdate commits; history is the audit trail. Currently 0/30, single `main` branch.
- With each day's commit: fill that day's 4 files + journal rows, flip its `⬜ Not started` cell in the root progress table, add evidence.
- Explanations in own words (1–3 sentences), not man-page copies. `TODO` markers mean unwritten.
- Lab baseline is Ubuntu 24.04 LTS: `apt`/`dpkg` is primary; `dnf`/`yum`/`rpm` (day-14) is comparison-only.
- No secrets, ever: no real passwords, private keys, tokens, internal IPs, or client data in files, evidence, or write-ups — placeholders only. Blocked by `.gitignore` (`*.pem`, `*.key`, `id_rsa*`, `id_ed25519*`, `*.ppk`, `.env*`); also ignored: `*.tmp`, `tmp/`, OS/editor noise.
- Least privilege by default: security drills (permissions, sudo, firewall, SSH) must note deliberate use and revert/document changes.
- LinkedIn `Article` column stays `_pending_` until the series index post exists.

## Gotchas

- `health-check.sh` must stay Bash-portable (`#!/usr/bin/env bash`, `chmod +x`), no hardcoded hosts/keys/credentials; log the full run per `day-30-capstone/drill.md`.
- `drill.md` code fences must contain the exact commands in run order, not a summary.
- This repo is edited from Windows/macOS hosts but documents Linux drills — do not add Linux-only tooling configs or convert line endings; keep Markdown + shell snippets plain.
