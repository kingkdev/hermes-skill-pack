---
name: comfyui-expert
description: Use when working with ComfyUI workflows, models, nodes, low-VRAM settings, Flux, SDXL, ControlNet, or image generation troubleshooting.
version: 2.0.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [comfyui, image-generation, flux, sdxl, low-vram]
    related_skills: [windows-cmd-development]
---

# Comfyui Expert

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

Use Windows paths and low-VRAM assumptions for RTX 4050 6GB unless the user says otherwise.

## Verification Checklist

- [ ] User's requested output format followed
- [ ] No unnecessary explanation
- [ ] No unnecessary files
- [ ] Windows CMD used where terminal commands are needed
- [ ] Next step is clear
