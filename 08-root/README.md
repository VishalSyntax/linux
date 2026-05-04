# 08 – Root

## What You'll Learn

- The root user (`uid=0`) and its privileges
- `sudo` vs `su`: configuration in `/etc/sudoers` (`visudo`)
- The principle of least privilege
- Restricting root login (SSH, console)
- Capabilities: `getcap`, `setcap` — granting fine-grained privileges without full root
- `chroot` jails
- Audit logging: `/var/log/auth.log`, `/var/log/secure`
- Common root-level tasks: package management, service management (`systemctl`)

## Logging Sessions

```bash
script -a logs/YYYY-MM-DD.log
exit
```

## Resources

- `man 8 sudo`
- `man 5 sudoers`
- `man 1 chroot`
