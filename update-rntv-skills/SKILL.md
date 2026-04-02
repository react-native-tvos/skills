---
name: Update RNTV Skills
description: Updates the RNTV skills installed on your computer. Supports switching between stable and main release branches.
allowed-tools: "Bash(**/update-rntv-skills/scripts/update.sh:*)"
version: 1.0.0
license: MIT License
---

# Update RNTV Skills

Updates the local clone of [@react-native-tvos/skills](https://github.com/react-native-tvos/skills) and reinstalls all skills.

## Updating

To update skills on the user's current branch:

```bash
{baseDir}/scripts/update.sh
```

## Handling Local Changes

If the user has uncommitted local changes, the script will not proceed. The user has several options:

1. **Stash changes**: Run `git stash` to temporarily save your changes, update, then `git stash pop` to restore them.
2. **Discard changes**: Run `git checkout -- .` to discard all uncommitted changes (cannot be undone).
3. **Commit changes**: If you want to keep them, commit them first with `git add -A && git commit -m "message"`.
