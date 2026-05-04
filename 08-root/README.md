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

- `man 8 sudo`
- `man 5 sudoers`
- `man 1 chroot`
