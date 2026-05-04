# 03 – Kernel

## What You'll Learn

- What the Linux kernel does (process scheduling, memory management, device I/O)
- Kernel version and release information: `uname -r`, `/proc/version`
- Kernel modules: `lsmod`, `modinfo`, `insmod`, `rmmod`, `modprobe`
- Kernel parameters at runtime: `/proc/sys`, `sysctl`
- Kernel ring buffer & logs: `dmesg`
- How to browse kernel source (optional deep-dive)

## Logging Sessions

```bash
script -a logs/YYYY-MM-DD.log
exit
```

## Resources

- `man 8 modprobe`
- `man 8 sysctl`
- <https://www.kernel.org/>
