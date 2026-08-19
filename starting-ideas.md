# Five larger topics

## Grep and regular expressions (this is the entre to the whole set, see below)

## Network troubleshooting

## Paths, aliases, and keeping your own ~/bin

## Pipes, especially 1\> & 2\>…

## Producivity tools at the CLI: calendar, taskwarrior, etc.

# Four x nine smaller topics (90s video candidates)

## Phase 1: Navigation & File Traps

| \# | Topic / Command | The 80/20 Focus (Common Mistake Addressed) |
|----|----|----|
| 1 | Tab Completion | You are typing too much; hit tab to avoid typos. |
| 2 | `cd -` & `~` | Stop typing full paths just to go back. |
| 3 | `mkdir -p` | Never get a "No such file or directory" error again. |
| 4 | `ls -lah` | The only flags you actually need (hidden files & human sizes). |
| 5 | `cp -r` | Why your directory stubbornly refuses to copy. |
| 6 | `mv` | It renames files; it does not just move them. |
| 7 | `rm -rf` vs `rm -i` | The danger zone and how to avoid deleting your work. |
| 8 | `find . -name` | Finding lost files without memorizing complex syntax. |
| 9 | `>` vs `>>` | Overwriting vs appending (do not nuke your configs). |

## Phase 2: Permissions & Text Viewing

| \# | Topic / Command | The 80/20 Focus (Common Mistake Addressed) |
|----|----|----|
| 10 | `sudo` | What it is, why it exists, and how it actually works. |
| 11 | `sudo su -` | The environment variable trap vs normal `su`. |
| 12 | `chmod +x` | Why your brand new script refuses to run. |
| 13 | `chmod 755/644` | The 80/20 of octal permissions explained simply. |
| 14 | `chown` | Fixing files you accidentally created as root. |
| 15 | `cat` vs `less` | Stop flooding your terminal screen with giant files. |
| 16 | `tail -f` | Watching live logs update in real-time. |
| 17 | `grep -i` | Case-insensitive searching (the number one `grep` mistake). |
| 18 | `grep -r` | Finding a specific string across an entire directory. |

## Phase 3: System & Network Panics

| \# | Topic / Command | The 80/20 Focus (Common Mistake Addressed) |
|----|----|----|
| 19 | `df -h` | Solving "Disk full" errors in human-readable terms. |
| 20 | `free -m` | Do you actually need more RAM? |
| 21 | `top` / `htop` | How to read the output without panicking. |
| 22 | `ps aux` & `grep` | Finding the exact rogue process you need to kill. |
| 23 | `kill -15` vs `-9` | Why you should not reach for -9 immediately. |
| 24 | `systemctl status` | Step one for troubleshooting broken background services. |
| 25 | `ip a` | Stop using `ifconfig=—it is deprecated.                        | | 26 | =ping` |
| 27 | `curl -O` vs `wget` | Grabbing files from the web quickly. |

## Phase 4: Customization & Workflow

| \# | Topic / Command | The 80/20 Focus (Common Mistake Addressed) |
|----|----|----|
| 28 | `Ctrl+R` | Reverse search is your absolute best friend. |
| 29 | Piping commands | The magic of stringing two commands together. |
| 30 | The `$PATH` | Why prioritizing `~/bin` changes everything. |
| 31 | Original Binaries | Forcing `/bin/mkdir` when you have aliased the command. |
| 32 | `date` Formats | Getting the timestamp format you actually want. |
| 33 | Enhancing `which` | Finding exactly which executable your shell is firing. |
| 34 | `alias` Basics | Saving thousands of keystrokes a week. |
| 35 | First Batch Script | Chaining these commands into a single executable file. |
