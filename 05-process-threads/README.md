# 05 – Process & Threads

## What You'll Learn

- Processes vs threads in Linux
- Process lifecycle: fork, exec, wait, exit
- Viewing processes: `ps aux`, `pstree`, `top`, `htop`
- Process IDs, parent PIDs, process groups, sessions
- Signals: `kill`, `killall`, `pkill`, `trap`
- `/proc/<pid>/` internals
- Threads with `pthread` basics (C) and how the kernel schedules them
- Inter-process communication (IPC): pipes, message queues, shared memory, sockets

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

- `man 5 proc`
- `man 7 signal`
- `man 2 fork`
