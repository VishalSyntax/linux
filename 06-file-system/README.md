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

## Logging Sessions

```bash
script -a logs/YYYY-MM-DD.log
exit
```

## Resources

- `man 5 fstab`
- `man 8 mount`
- `man 1 chmod`
