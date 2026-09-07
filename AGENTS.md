# Antigravity Workspace Guidelines

## Critical Git Remote Push Policy (Strict Invariant)
- **NEVER execute `git push` without explicit user instruction in the current prompt.**
- **ONLY repositories permitted to ever be pushed to a remote are:**
  1. `hexdef` (`shadowpbx.github.io`)
  2. `hexlean` (`hexlean`)
- **NEVER push authoring repositories** (such as `learn-c-az`, `learn-bash-az`, `learn-python-az`, etc.) or any other repository to any remote. Only local commits are permitted for authoring repos.
- Even for `hexdef` and `hexlean`, **DO NOT push proactively**—always wait for the user to explicitly say "push to github" or provide instructions to push.
