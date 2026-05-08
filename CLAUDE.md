# CLAUDE.md

This file provides guidance for AI assistants (Claude and others) working in this repository.

## Repository Overview

`paulnlnl/paulnlnl` is a **GitHub profile repository**. Because the repository name matches the GitHub username, GitHub automatically renders its `README.md` as the public profile page at `github.com/paulnlnl`. The primary artifact here is that `README.md`.

## File Structure

```
paulnlnl/paulnlnl
├── README.md        # GitHub profile page (rendered publicly on the profile)
├── CLAUDE.md        # This file — AI assistant guidance
└── assets/          # Optional: images or media referenced by README.md
```

There is no application code, build system, test suite, or dependency manifest. All meaningful content lives in `README.md`.

## Development Workflow

1. Edit `README.md` (and any supporting assets) on a feature branch.
2. Commit with a clear message describing what changed.
3. Push to the remote and open a PR if review is desired, or push directly to `main` for simple updates.

Since this is a profile repository, "shipping" means merging to `main` — GitHub picks up changes immediately.

## Conventions

### Branch Naming
Use descriptive prefixes:
- `claude/` — branches created by AI assistants (e.g., `claude/update-readme`)
- `feat/` — new profile sections or features
- `fix/` — corrections to existing content

### Commit Messages
Use short, imperative-mood messages in plain prose:
```
Add skills section to README
Update project highlights
Fix broken badge link
```

Avoid generic messages like "update README" without context.

### README Style
- The profile is **public-facing** — keep tone professional yet personal.
- Use GitHub-flavored Markdown (GFM): badges, tables, and collapsible sections are supported.
- Prefer concise content; visitors skim profile pages.
- Alt text on all images for accessibility.

## Notes for AI Assistants

- **No linting, tests, or build steps** — there is nothing to run. Skip any setup/test verification steps.
- **No dependencies to install** — no `package.json`, `requirements.txt`, or similar files.
- **Primary task** is editing `README.md`. Read its current contents before making changes.
- **Tone**: Public profile content should reflect the owner's personal brand. When in doubt, ask the user about voice and style rather than assuming.
- **Images/assets**: If adding images, place them in `assets/` and reference them with relative paths so they work on any branch.
- **Branch**: New AI work goes on a `claude/` branch; push to that branch and let the user merge.
