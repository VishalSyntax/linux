# 04 – Namespaces

## What You'll Learn

- What Linux namespaces are and why they matter (foundation of containers)
- Types of namespaces: PID, Network, Mount, UTS, IPC, User, Cgroup
- Exploring namespaces: `lsns`, `/proc/<pid>/ns/`
- Creating namespaces: `unshare`, `nsenter`
- How Docker/Podman use namespaces under the hood

## Logging Sessions

```bash
script -a logs/YYYY-MM-DD.log
exit
```

## Resources

- `man 7 namespaces`
- `man 1 unshare`
- `man 1 nsenter`
