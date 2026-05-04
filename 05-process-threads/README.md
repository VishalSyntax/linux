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

## Logging Sessions

```bash
script -a logs/YYYY-MM-DD.log
exit
```

## Resources

- `man 5 proc`
- `man 7 signal`
- `man 2 fork`
