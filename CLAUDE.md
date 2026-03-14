# CLAUDE.md

## Commit conventions

- Prefix every commit message with 🤗 emoji (e.g. `🤗 Add jobs command coverage`)

## Publishing to ClawHub

After updating `skill/SKILL.md`, publish with:

```bash
npx clawhub publish ./skill --slug hugging-face-cli --name "Hugging Face CLI" --version <version> --changelog "<description>"
```

- Bump version using semver (patch for fixes, minor for new commands, major for breaking changes)
- Login first if needed: `npx clawhub login`
- Verify with: `npx clawhub whoami`
