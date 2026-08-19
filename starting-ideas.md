<div id="content" class="content">

<div id="table-of-contents" role="doc-toc">

## Table of Contents

<div id="text-table-of-contents" role="doc-toc">

- [1. Five larger topics](#org7af6893)
  - [1.1. Grep and regular expressions (this is the entre to the whole
    set, see below)](#org53130e5)
  - [1.2. Network troubleshooting](#org5241302)
  - [1.3. Paths, aliases, and keeping your own ~/bin](#org92f3606)
  - [1.4. Pipes, especially 1\> & 2\>…](#org5008a56)
  - [1.5. Producivity tools at the CLI: calendar, taskwarrior,
    etc.](#orgf2d3a9b)
- [2. Four x nine smaller topics (90s video candidates)](#org6d26eea)
  - [2.1. Phase 1: Navigation & File Traps](#orgc338db0)
  - [2.2. Phase 2: Permissions & Text Viewing](#orgc97d4df)
  - [2.3. Phase 3: System & Network Panics](#org39d2a4e)
  - [2.4. Phase 4: Customization & Workflow](#org49a585e)

</div>

</div>

<div id="outline-container-org7af6893" class="outline-2">

## <span class="section-number-2">1.</span> Five larger topics

<div id="text-1" class="outline-text-2">

</div>

<div id="outline-container-org53130e5" class="outline-3">

### <span class="section-number-3">1.1.</span> Grep and regular expressions (this is the entre to the whole set, see below)

</div>

<div id="outline-container-org5241302" class="outline-3">

### <span class="section-number-3">1.2.</span> Network troubleshooting

</div>

<div id="outline-container-org92f3606" class="outline-3">

### <span class="section-number-3">1.3.</span> Paths, aliases, and keeping your own ~/bin

</div>

<div id="outline-container-org5008a56" class="outline-3">

### <span class="section-number-3">1.4.</span> Pipes, especially 1\> & 2\>…

</div>

<div id="outline-container-orgf2d3a9b" class="outline-3">

### <span class="section-number-3">1.5.</span> Producivity tools at the CLI: calendar, taskwarrior, etc.

</div>

</div>

<div id="outline-container-org6d26eea" class="outline-2">

## <span class="section-number-2">2.</span> Four x nine smaller topics (90s video candidates)

<div id="text-2" class="outline-text-2">

</div>

<div id="outline-container-orgc338db0" class="outline-3">

### <span class="section-number-3">2.1.</span> Phase 1: Navigation & File Traps

<div id="text-2-1" class="outline-text-3">

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

</div>

</div>

<div id="outline-container-orgc97d4df" class="outline-3">

### <span class="section-number-3">2.2.</span> Phase 2: Permissions & Text Viewing

<div id="text-2-2" class="outline-text-3">

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

</div>

</div>

<div id="outline-container-org39d2a4e" class="outline-3">

### <span class="section-number-3">2.3.</span> Phase 3: System & Network Panics

<div id="text-2-3" class="outline-text-3">

| \# | Topic / Command | The 80/20 Focus (Common Mistake Addressed) |
|----|----|----|
| 19 | `df -h` | Solving "Disk full" errors in human-readable terms. |
| 20 | `free -m` | Do you actually need more RAM? |
| 21 | `top` / `htop` | How to read the output without panicking. |
| 22 | `ps aux` & `grep` | Finding the exact rogue process you need to kill. |
| 23 | `kill -15` vs `-9` | Why you should not reach for -9 immediately. |
| 24 | `systemctl status` | Step one for troubleshooting broken background services. |
| 25 | `ip a` | Stop using =ifconfig=—it is deprecated. |
| 26 | `ping` | Testing DNS resolution versus IP routing. |
| 27 | `curl -O` vs `wget` | Grabbing files from the web quickly. |

</div>

</div>

<div id="outline-container-org49a585e" class="outline-3">

### <span class="section-number-3">2.4.</span> Phase 4: Customization & Workflow

<div id="text-2-4" class="outline-text-3">

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

</div>

</div>

</div>

</div>

<div id="postamble" class="status">

Author: William Orian Wear

Created: 2026-08-19 Wed 12:18

[Validate](https://validator.w3.org/check?uri=referer)

</div>
