# Coddo Documentation

Official documentation for [Coddo](https://coddo.ai) -the visual interface for Claude Code.

## Structure

```
index.mdx              # Introduction
installation.mdx       # Installation guide
quickstart.mdx         # Quick start guide
features/
├── chat.mdx           # Chat interface
├── kanban.mdx         # Kanban board
├── git.mdx            # Git integration
├── skills.mdx         # Skills system
├── stats.mdx          # Statistics & analytics
├── claude-md.mdx      # CLAUDE.md editor
└── settings.mdx       # Settings & preferences
guides/
├── first-project.mdx  # Creating your first project
├── task-workflow.mdx   # Task lifecycle guide
└── git-workflow.mdx    # Git workflow guide
```

## Development

```bash
npm i -g mint
mint dev
```

Preview at `http://localhost:3000`.

## Deployment

Changes pushed to the default branch are deployed automatically via the Mintlify GitHub app.
