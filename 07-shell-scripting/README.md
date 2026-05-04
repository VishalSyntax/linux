# 07 – Shell Scripting

## What You'll Learn

- Shell types and choosing a shell: bash, sh, zsh
- Script structure: shebang (`#!/bin/bash`), comments, execution permissions
- Variables, arrays, and environment variables
- Control flow: `if/elif/else`, `case`
- Loops: `for`, `while`, `until`
- Functions
- Input / output: `read`, `echo`, `printf`
- String manipulation and arithmetic
- Exit codes and error handling (`set -e`, `trap`)
- Scheduling scripts: `cron`, `at`
- Practical scripts: backup, log rotation, user management

## Folder Contents

| Folder | Purpose |
|--------|---------|
| `logs/` | Terminal session recordings (`script` command) |
| `screenshots/` | Screenshots taken during the session |
| `notes/notes.md` | Written notes organised by sub-topic |
| `questions/questions.md` | Most important questions to test understanding |

## Logging a Session

```bash
script -a logs/YYYY-MM-DD.log
exit
```

Save screenshots to `screenshots/` and fill in `notes/notes.md` as you go.

## Resources

- `man bash`
- <https://www.shellcheck.net/> (linter for shell scripts)
