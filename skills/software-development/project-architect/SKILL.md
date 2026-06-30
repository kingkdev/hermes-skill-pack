---
name: project-architect
description: Use when starting or restructuring a project and deciding folder layout, file boundaries, naming, dependencies, and implementation sequence.
version: 1.1.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [architecture, project-structure, planning, files, software-development]
    related_skills: [windows-cmd-development, local-coding-agent, plan]
---
# Project Architect

## Overview

Designs clean project structures before code is written.

## When to Use

Use for new projects, messy folders, unclear file organization, or when the user wants Hermes to build something from scratch.

## Principles

- Create the smallest useful structure.
- Separate HTML, CSS, JavaScript, assets, tests, and docs when appropriate.
- Avoid overengineering.
- Make the project easy for Hermes to edit later.

## Standard Web Project

```text
project-name/
├── index.html
├── style.css
├── app.js
├── assets/
└── README.md
```

## Verification Checklist

- [ ] Folder structure matches task
- [ ] Files have clear purpose
- [ ] No unnecessary complexity
