

## Resolving common git issues

- If merge conflicts appear in Source Control but there are no conflicts to resolve (e.g. no "Accept Incoming" prompts in the editor) then use `Dendron: Reload Index` and then `Dendron: Workspace Sync`.
- To resolve legitimate merge issues:
  - Open file with conflicts and accept or reject changes.
  - Stage the file.
    - VS Code should automatically complete commit here, but sometimes it fails.
  - Commit changes.
  - Push to remote.
