---
name: local-coding-agent
description: Use when building, modifying, debugging, or maintaining software projects on the user's local Windows development environment.
version: 1.1.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [coding, windows, vscode, git, python, nodejs, debugging]
    related_skills: [windows-cmd-development, plan, systematic-debugging, requesting-code-review]
---
# Local Coding Agent

## Overview

This skill makes Hermes act like a local software engineer that can plan, edit, test, debug, and verify projects.

## When to Use

Use when the user asks to build a website, create an app, edit code, debug errors, add features, refactor, or review code.

## Workflow

1. Understand the request.
2. Inspect the project.
3. Make a short implementation plan.
4. Change one logical thing.
5. Verify.
6. Continue.

## Rules

- Prefer readable code.
- Reuse existing files before creating new ones.
- Keep project structure clean.
- Verify after changes.
- Use Windows CMD commands through the `windows-cmd-development` skill.

## Verification Checklist

- [ ] Request understood
- [ ] Project inspected
- [ ] Plan created
- [ ] Code changed
- [ ] Verified
