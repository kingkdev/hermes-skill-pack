---
name: code-reviewer
description: Use when reviewing code for quality, bugs, security, accessibility, performance, or maintainability.
version: 2.0.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [code-review, quality, security]
    related_skills: [requesting-code-review, bug-hunter]
---

# Code Reviewer

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

Review meaningful issues only. Provide concise fixes. Do not rewrite everything unless requested.

## Verification Checklist

- [ ] User's requested output format followed
- [ ] No unnecessary explanation
- [ ] No unnecessary files
- [ ] Windows CMD used where terminal commands are needed
- [ ] Next step is clear
