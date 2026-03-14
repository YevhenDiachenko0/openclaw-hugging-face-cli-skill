# Changelog

## 1.1.0 — 2026-03-14

- Add alternative installation methods: pip (recommended), Homebrew, and uvx
- Move standalone `curl | bash` installer to Option 4
- Add Windows PowerShell installer

## 1.0.0 — 2026-03-14

Initial release targeting `hf` CLI v1.7.1.

- 48 commands covering: repos, models, datasets, spaces, jobs, endpoints, papers, collections, discussions, buckets, cache, and sync
- Safety rules for all destructive operations (delete repos, endpoints, collections, cancel jobs, etc.)
- Token permission guidance (read vs write) with clear recommendations
- Installation instructions for macOS, Linux, and Windows
- 3 end-to-end examples tested against live CLI
- OpenClaw metadata with brew install spec and runtime requirements
