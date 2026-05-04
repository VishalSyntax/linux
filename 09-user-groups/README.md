# 09 – User & Groups

## What You'll Learn

- User account files: `/etc/passwd`, `/etc/shadow`
- Group files: `/etc/group`, `/etc/gshadow`
- Managing users: `useradd`, `usermod`, `userdel`, `passwd`
- Managing groups: `groupadd`, `groupmod`, `groupdel`
- Switching users: `su`, `sudo -u`
- Viewing identity: `id`, `whoami`, `groups`, `w`, `who`, `last`
- File ownership and permissions revisited in the context of users/groups
- Password policies: `chage`, PAM basics

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

- `man 5 passwd`
- `man 8 useradd`
- `man 8 groupadd`
