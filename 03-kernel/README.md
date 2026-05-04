# 03 – Kernel

## What You'll Learn

- What the Linux kernel does (process scheduling, memory management, device I/O)
- Kernel version and release information: `uname -r`, `/proc/version`
- Kernel modules: `lsmod`, `modinfo`, `insmod`, `rmmod`, `modprobe`
- Kernel parameters at runtime: `/proc/sys`, `sysctl`
- Kernel ring buffer & logs: `dmesg`
- How to browse kernel source (optional deep-dive)

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

- `man 8 modprobe`
- `man 8 sysctl`
- <https://www.kernel.org/>
