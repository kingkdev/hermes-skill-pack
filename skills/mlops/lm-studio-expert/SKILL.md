---
name: lm-studio-expert
description: Use when configuring LM Studio, local models, OpenAI-compatible local server, model selection, context size, GPU usage, or local AI coding workflows.
version: 1.1.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [lmstudio, local-ai, models, openai-compatible, gpu]
    related_skills: [windows-cmd-development, llama-cpp, local-coding-agent]
---
# LM Studio Expert

## Overview

Helps configure LM Studio for local AI workflows.

## When to Use

Use for loading models, starting the local server, connecting tools to the OpenAI-compatible endpoint, choosing models, and troubleshooting GPU/VRAM issues.

## Rules

- Match model size to available VRAM.
- Prefer coding models for coding tasks.
- Confirm local server is running before blaming the client app.

## Verification Checklist

- [ ] Model loaded
- [ ] Local server enabled
- [ ] Endpoint reachable
- [ ] Correct model selected
