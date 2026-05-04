# 04 – Namespaces

## What You'll Learn

- What Linux namespaces are and why they matter (foundation of containers)
- Types of namespaces: PID, Network, Mount, UTS, IPC, User, Cgroup
- Exploring namespaces: `lsns`, `/proc/<pid>/ns/`
- Creating namespaces: `unshare`, `nsenter`
- How Docker/Podman use namespaces under the hood

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

- `man 7 namespaces`
- `man 1 unshare`
- `man 1 nsenter`
