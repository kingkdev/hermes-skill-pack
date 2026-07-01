---
name: n8n-automation
description: Use when designing, debugging, or explaining n8n workflows, triggers, nodes, APIs, credentials, or business automation.
version: 2.0.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [n8n, automation, workflows, api]
    related_skills: [windows-cmd-development, local-coding-agent]
---

# N8N Automation

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

Define trigger, node sequence, data mapping, credentials, error path, and test step.

## Verification Checklist

- [ ] User's requested output format followed
- [ ] No unnecessary explanation
- [ ] No unnecessary files
- [ ] Windows CMD used where terminal commands are needed
- [ ] Next step is clear
