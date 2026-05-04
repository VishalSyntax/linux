# 02 – Basic & Advanced Commands

## What You'll Learn

### Basic Commands
- Navigation: `pwd`, `ls`, `cd`
- File operations: `touch`, `cp`, `mv`, `rm`, `mkdir`, `rmdir`
- Viewing files: `cat`, `less`, `more`, `head`, `tail`
- Help: `man`, `info`, `--help`
- Searching: `find`, `locate`, `which`, `whereis`

### Advanced Commands
- Text processing: `grep`, `sed`, `awk`, `cut`, `sort`, `uniq`, `wc`
- Archiving & compression: `tar`, `gzip`, `bzip2`, `zip`
- Network utilities: `ping`, `curl`, `wget`, `ss`, `netstat`, `ip`
- Process management: `ps`, `top`, `htop`, `kill`, `jobs`, `bg`, `fg`
- Disk usage: `df`, `du`
- Pipes and redirection: `|`, `>`, `>>`, `<`, `2>&1`

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
