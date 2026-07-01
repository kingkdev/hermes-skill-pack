---
name: full-stack-website-builder
description: Use when building complete websites or web apps from plan to files.
version: 2.0.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [website, full-stack, frontend, backend]
    related_skills: [html-css-js-expert, project-architect, local-coding-agent]
---

# Full Stack Website Builder

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

Build frontend first. Add backend only when required. Verify the main user flow before calling the task complete.

## Verification Checklist

- [ ] User's requested output format followed
- [ ] No unnecessary explanation
- [ ] No unnecessary files
- [ ] Windows CMD used where terminal commands are needed
- [ ] Next step is clear
