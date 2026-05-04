# 01 – Introduction

## What You'll Learn

- What is Linux and its history
- Linux distributions (Debian, Ubuntu, Fedora, Arch, etc.)
- Linux architecture overview: hardware → kernel → shell → user space
- How to install / set up a Linux environment (VM, WSL, bare-metal)
- The Linux file-system hierarchy at a glance
- Basic terminal navigation: opening a terminal, the prompt, `man` pages

## Folder Contents

| Folder | Purpose |
|--------|---------|
| `logs/` | Terminal session recordings (`script` command) |
| `screenshots/` | Screenshots taken during the session |
| `notes/notes.md` | Written notes organised by sub-topic |
| `questions/questions.md` | Most important questions to test understanding |

## Logging a Session

```bash
# Record terminal session
script -a logs/YYYY-MM-DD.log
# … explore, run commands …
exit
```

Save screenshots to `screenshots/` and fill in `notes/notes.md` as you go.

## Resources

- `man intro`
- `man hier` (file-system hierarchy)
- <https://www.kernel.org/doc/html/latest/admin-guide/README.html>
