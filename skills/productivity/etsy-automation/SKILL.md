---
name: etsy-automation
description: Use when building Etsy workflows for wall art, listings, SEO, tags, mockups, descriptions, prompts, or batching.
version: 2.0.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [etsy, seo, listings, wall-art, automation]
    related_skills: [ux-ui-designer, html-css-js-expert]
---

# Etsy Automation

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

Define product, create SEO title, tags, description, mockup direction, and packaging checklist.

## Verification Checklist

- [ ] User's requested output format followed
- [ ] No unnecessary explanation
- [ ] No unnecessary files
- [ ] Windows CMD used where terminal commands are needed
- [ ] Next step is clear
