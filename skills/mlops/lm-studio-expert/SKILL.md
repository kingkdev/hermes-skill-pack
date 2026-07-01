---
name: lm-studio-expert
description: Use when configuring LM Studio, local models, OpenAI-compatible server, model selection, context length, GPU offload, or local AI workflows.
version: 2.0.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [lmstudio, local-ai, models, gpu, openai-compatible]
    related_skills: [windows-cmd-development, local-coding-agent]
---

# Lm Studio Expert

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

Use http://127.0.0.1:1234/v1 when Hermes and LM Studio run on the same PC. Prefer qwen2.5-coder-7b-instruct for coding. Avoid models that only return reasoning_content without normal content.

## Verification Checklist

- [ ] User's requested output format followed
- [ ] No unnecessary explanation
- [ ] No unnecessary files
- [ ] Windows CMD used where terminal commands are needed
- [ ] Next step is clear
