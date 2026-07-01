---
name: project-architect
description: Use when deciding folder structure, file names, implementation order, dependencies, or project organization.
version: 2.0.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [architecture, project-structure, planning, files]
    related_skills: [windows-cmd-development, local-coding-agent]
---

# Project Architect

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

Design the simplest useful structure.

For a simple HTML website, default to exactly:

index.html
style.css
script.js

Do not add about.html, contact.html, blog/, assets/, or images/ unless the user asks for them.

## Verification Checklist

- [ ] User's requested output format followed
- [ ] No unnecessary explanation
- [ ] No unnecessary files
- [ ] Windows CMD used where terminal commands are needed
- [ ] Next step is clear
