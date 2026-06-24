# Workspace Rules

These rules apply to Codex-generated development projects on this machine.

## Default Project Location

Use this folder for new development projects:

```text
C:\Users\LINJO\CodexProjects
```

## Avoid OneDrive for Development Outputs

Do not create development projects, dependency folders, build outputs, or `node_modules` under any OneDrive folder unless explicitly requested.

Reason:

- avoids sync conflicts
- keeps dependency folders local and fast
- reduces accidental cloud upload of large build artifacts

## Project Setup Checklist

For each new project:

1. Create the project under `C:\Users\LINJO\CodexProjects`.
2. Keep source code, config, and docs in the project folder.
3. Keep temporary analysis in a scratch or work folder when needed.
4. Do not store secrets in the repository.
5. Add a short README before the project grows.
