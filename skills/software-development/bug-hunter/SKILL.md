---
name: bug-hunter
description: Use when diagnosing errors, failed commands, stack traces, broken code, or unexpected behavior.
version: 2.0.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [debugging, errors, root-cause]
    related_skills: [systematic-debugging, local-coding-agent]
---

# Bug Hunter

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

Find root cause before fixing. Apply one fix at a time. Verify the error is gone. Do not shotgun multiple unrelated fixes.

## Verification Checklist

- [ ] User's requested output format followed
- [ ] No unnecessary explanation
- [ ] No unnecessary files
- [ ] Windows CMD used where terminal commands are needed
- [ ] Next step is clear
