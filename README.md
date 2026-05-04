# Linux Learning Journal

A day-by-day log of learning Linux, following the syllabus below.  
Each session's terminal output is captured with the `script` command and committed here.

---

## Folder Layout (per topic)

```
<topic>/
├── logs/          # Terminal session recordings (script command output)
├── screenshots/   # Screenshots taken during the session
├── notes/
│   └── notes.md   # Written notes organised by sub-topic
└── questions/
    └── questions.md  # Most important questions to test understanding
```

## How to Log a Session

```bash
# Start recording terminal session
script -a <topic>/logs/YYYY-MM-DD.log

# ... run your commands ...

# Stop recording
exit
```

Add screenshots to `<topic>/screenshots/` and fill in `notes/notes.md` as you go.

Push after every session:
```bash
git add .
git commit -m "Day N – <topic>: <short description>"
git push
```

---

## Syllabus

| # | Topic | Folder |
|---|-------|--------|
| 1 | Introduction | [01-introduction/](01-introduction/) |
| 2 | Basic & Advanced Commands | [02-basic-advanced-commands/](02-basic-advanced-commands/) |
| 3 | Kernel | [03-kernel/](03-kernel/) |
| 4 | Namespaces | [04-namespaces/](04-namespaces/) |
| 5 | Process & Threads | [05-process-threads/](05-process-threads/) |
| 6 | File System | [06-file-system/](06-file-system/) |
| 7 | Shell Scripting | [07-shell-scripting/](07-shell-scripting/) |
| 8 | Root | [08-root/](08-root/) |
| 9 | User & Groups | [09-user-groups/](09-user-groups/) |

---

## Progress

- [ ] 01 – Introduction
- [ ] 02 – Basic & Advanced Commands
- [ ] 03 – Kernel
- [ ] 04 – Namespaces
- [ ] 05 – Process & Threads
- [ ] 06 – File System
- [ ] 07 – Shell Scripting
- [ ] 08 – Root
- [ ] 09 – User & Groups
