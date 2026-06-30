---
name: bug-hunter
description: Use when diagnosing errors, broken code, failed commands, terminal output, stack traces, or unexpected app behavior.
version: 1.1.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [debugging, errors, root-cause, troubleshooting]
    related_skills: [systematic-debugging, windows-cmd-development, local-coding-agent]
---
# Bug Hunter

## Overview

Finds root cause before fixing.

## Process

1. Read the whole error.
2. Identify the failing layer.
3. Find the root cause.
4. Apply one fix.
5. Verify.
6. Prevent regression when possible.

## Rules

- Do not guess.
- Do not shotgun fixes.
- Do not skip verification.

## Verification Checklist

- [ ] Root cause identified
- [ ] Fix applied
- [ ] Error no longer appears
