---
name: windows-cmd-development
description: Use when Windows CMD commands, Windows paths, Python, Git, Node.js, VS Code, LM Studio, llama.cpp, local AI tooling, or terminal troubleshooting are required.
version: 2.0.0
author: Kishon Dowell
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [windows, cmd, command-prompt, python, git, nodejs, vscode, lmstudio, local-ai]
    related_skills: [plan, systematic-debugging, requesting-code-review, llama-cpp]
---

# Windows Cmd Development

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

Default to Windows Command Prompt (`cmd.exe`). Never use PowerShell, Bash, Linux, macOS, WSL, or Unix commands unless explicitly requested.

Use CMD commands such as:

dir
cd C:\Users\king\Projects
mkdir TestSite
type nul > index.html
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

When asked for one command, output exactly one CMD command with no explanation.

## Verification Checklist

- [ ] User's requested output format followed
- [ ] No unnecessary explanation
- [ ] No unnecessary files
- [ ] Windows CMD used where terminal commands are needed
- [ ] Next step is clear
