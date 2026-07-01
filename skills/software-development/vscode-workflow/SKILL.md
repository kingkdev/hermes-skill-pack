---
name: vscode-workflow
description: Use when opening, running, editing, or debugging projects in VS Code on Windows.
version: 2.0.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [vscode, editor, workflow, windows]
    related_skills: [windows-cmd-development, local-coding-agent]
---

# Vscode Workflow

## Output Contract

Follow the user's requested output shape exactly.

If the user asks for:
- one command: output one command only
- only filenames: output filenames only
- no explanation: do not explain
- no code: do not include code
- wait for approval: stop after the plan

Do not add examples, alternatives, markdown fences, explanations, or extra commentary unless requested.


## Core Behavior

Use `code .` to open projects. Prefer CMD terminal. Select `.venv` interpreter for Python projects.

## Verification Checklist

- [ ] User's requested output format followed
- [ ] No unnecessary explanation
- [ ] No unnecessary files
- [ ] Windows CMD used where terminal commands are needed
- [ ] Next step is clear
