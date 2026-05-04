# 06 – File System

## What You'll Learn

- Linux file-system types: ext4, xfs, btrfs, tmpfs, proc, sysfs
- The Virtual File System (VFS) layer
- Inodes, hard links, soft links: `ln`
- Mounting and unmounting: `mount`, `umount`, `/etc/fstab`
- Disk partitioning: `fdisk`, `parted`, `lsblk`, `blkid`
- Permissions and ownership: `chmod`, `chown`, `chgrp`, `umask`
- Special permissions: SUID, SGID, sticky bit
- Checking disk usage: `df -h`, `du -sh`
- File attributes: `lsattr`, `chattr`

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

- `man 5 fstab`
- `man 8 mount`
- `man 1 chmod`
