---
name: windows-cmd-development
description: Use when working on Windows development tasks that require Command Prompt commands, Windows-native tooling, Python virtual environments, Git, Node.js, VS Code, LM Studio, llama.cpp, file operations, terminal troubleshooting, or local AI development.
version: 1.1.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [windows, cmd, command-prompt, python, git, nodejs, vscode, lmstudio, llama-cpp, local-ai, troubleshooting]
    related_skills: [plan, systematic-debugging, requesting-code-review, github-auth, github-repo-management, llama-cpp]
---
# Windows CMD Development Expert

## Overview

This skill makes Hermes Windows-first. Assume Windows Command Prompt (`cmd.exe`) unless the user explicitly asks for PowerShell, Linux, macOS, Bash, or WSL.

## When to Use

Use for Windows commands, Python setup, Git, Node.js, VS Code, LM Studio, llama.cpp, file operations, and terminal troubleshooting.

## Command Rules

Use CMD syntax:

```cmd
dir
cd C:\Users\king\Projects
mkdir my-project
copy file.txt backup.txt
move file.txt archive\
del file.txt
rmdir /S /Q build
where python
python -m venv .venv
.venv\Scripts\activate
npm install
npm run dev
git status
code .
```

Never use Linux syntax unless requested:

```text
ls
pwd
rm
mv
cp
touch
chmod
source .venv/bin/activate
```

## Response Format

Give one clear step at a time:

1. What this does
2. CMD command
3. Expected result
4. Next step

## Verification Checklist

- [ ] CMD syntax only
- [ ] Windows paths
- [ ] Copy/paste ready
- [ ] Expected result included
- [ ] One next step
