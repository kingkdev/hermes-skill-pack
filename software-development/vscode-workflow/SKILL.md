---
name: vscode-workflow
description: Use when opening, editing, running, testing, or debugging projects inside Visual Studio Code on Windows.
version: 1.1.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [vscode, editor, workflow, windows, debugging]
    related_skills: [windows-cmd-development, local-coding-agent]
---
# VS Code Workflow

## Overview

Guides Hermes to work cleanly with VS Code on Windows.

## When to Use

Use when the user asks how to open a project, run code, use the terminal, select Python interpreter, or test a web project.

## Core Commands

```cmd
code .
```

For Python projects, select the `.venv` interpreter.

For web projects, open `index.html` in browser or run a dev server when needed.

## Verification Checklist

- [ ] Correct folder opened
- [ ] Terminal uses CMD when requested
- [ ] Interpreter selected when Python is used
