# Command Journal

My running log of all 300 commands: one line each, in my own words, plus one thing that surprised me or one mistake I made (Appendix A of the brief).

## Day 01: Where Am I? Basic Orientation

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `pwd` | Shows me the present working directory — it tells me exactly where I am in the filesystem right now. | Nothing unexpected. |
| 2 | `ls` | Lists the contents of the current directory. By default it puts many files on the same row to save space. | I thought `ls` was broken because files were squashed into rows — turns out that is just its default multi-column layout. |
| 3 | `ls -l` | Long format listing. Shows permissions, owner, size, and date in separate columns for each file. | Nothing unexpected. |
| 4 | `ls -a` | Shows all files, including hidden ones that start with a dot. | Nothing unexpected. |
| 5 | `ls -la` | Combines long format and show-all — I get every hidden file with full details. | Nothing unexpected. |
| 6 | `ls -lh` | Long format with human-readable sizes, like `4.3K` instead of just a raw number. | Nothing unexpected. |
| 7 | `cd (absolute path)` | Changes my current directory to any location I give it as a full path starting from `/`. | Nothing unexpected. |
| 8 | `cd ..` | Moves me one directory up — one step backward in the tree. | Nothing unexpected. |
| 9 | `cd ~` | Takes me straight back to my home directory from anywhere in the filesystem. | I did not know I could go home this easily — I thought I had to type the full path every time. |
| 10 | `cd -` | Jumps back to the last directory I was in. It toggles between two locations. | Nothing unexpected. |

## Day 02: Creating, Copying, Moving, Deleting

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `mkdir` | TODO | TODO |
| 2 | `mkdir -p` | TODO | TODO |
| 3 | `touch` | TODO | TODO |
| 4 | `cp` | TODO | TODO |
| 5 | `cp -r` | TODO | TODO |
| 6 | `mv` | TODO | TODO |
| 7 | `rm` | TODO | TODO |
| 8 | `rm -r` | TODO | TODO |
| 9 | `rm -rf` | TODO | TODO |
| 10 | `rmdir` | TODO | TODO |

## Day 03: Reading & Inspecting Files

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `cat` | TODO | TODO |
| 2 | `less` | TODO | TODO |
| 3 | `head` | TODO | TODO |
| 4 | `head -n` | TODO | TODO |
| 5 | `tail` | TODO | TODO |
| 6 | `tail -f` | TODO | TODO |
| 7 | `wc` | TODO | TODO |
| 8 | `wc -l` | TODO | TODO |
| 9 | `file` | TODO | TODO |
| 10 | `stat` | TODO | TODO |

## Day 04: Searching the Filesystem

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `find -name` | TODO | TODO |
| 2 | `find -type` | TODO | TODO |
| 3 | `find -size` | TODO | TODO |
| 4 | `find -mtime` | TODO | TODO |
| 5 | `find -perm` | TODO | TODO |
| 6 | `locate` | TODO | TODO |
| 7 | `updatedb` | TODO | TODO |
| 8 | `du` | TODO | TODO |
| 9 | `du -sh` | TODO | TODO |
| 10 | `df -h` | TODO | TODO |

## Day 05: Paths, Links & Tree Structures

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `tree` | TODO | TODO |
| 2 | `tree -L` | TODO | TODO |
| 3 | `ln (hard link)` | TODO | TODO |
| 4 | `ln -s (symbolic link)` | TODO | TODO |
| 5 | `readlink` | TODO | TODO |
| 6 | `realpath` | TODO | TODO |
| 7 | `basename` | TODO | TODO |
| 8 | `dirname` | TODO | TODO |
| 9 | `pushd / popd` | TODO | TODO |
| 10 | `ls -lt` | TODO | TODO |

## Day 06: Reading & Setting Permissions

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `ls -l (permission string)` | TODO | TODO |
| 2 | `chmod (relative +/-)` | TODO | TODO |
| 3 | `chmod (assignment =)` | TODO | TODO |
| 4 | `chmod 755 (octal)` | TODO | TODO |
| 5 | `chmod 644 (octal)` | TODO | TODO |
| 6 | `chmod 600 (octal)` | TODO | TODO |
| 7 | `chmod -R` | TODO | TODO |
| 8 | `umask` | TODO | TODO |
| 9 | `umask -S` | TODO | TODO |
| 10 | `stat -c '%A %U %G'` | TODO | TODO |

## Day 07: Ownership & Special Bits

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `chown` | TODO | TODO |
| 2 | `chown user:group` | TODO | TODO |
| 3 | `chown -R` | TODO | TODO |
| 4 | `chgrp` | TODO | TODO |
| 5 | `chmod u+s (SUID)` | TODO | TODO |
| 6 | `chmod g+s (SGID)` | TODO | TODO |
| 7 | `chmod +t (sticky bit)` | TODO | TODO |
| 8 | `find -perm /4000` | TODO | TODO |
| 9 | `getfacl` | TODO | TODO |
| 10 | `setfacl -m` | TODO | TODO |

## Day 08: Privilege Escalation & Identity

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `sudo` | TODO | TODO |
| 2 | `sudo -i` | TODO | TODO |
| 3 | `sudo -u` | TODO | TODO |
| 4 | `sudo !!` | TODO | TODO |
| 5 | `sudo -l` | TODO | TODO |
| 6 | `visudo` | TODO | TODO |
| 7 | `su` | TODO | TODO |
| 8 | `su -` | TODO | TODO |
| 9 | `whoami` | TODO | TODO |
| 10 | `id` | TODO | TODO |

## Day 09: Integrity, Encryption & Firewalling

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `md5sum` | TODO | TODO |
| 2 | `sha256sum` | TODO | TODO |
| 3 | `gpg --gen-key` | TODO | TODO |
| 4 | `gpg --encrypt` | TODO | TODO |
| 5 | `gpg --decrypt` | TODO | TODO |
| 6 | `chattr +i` | TODO | TODO |
| 7 | `lsattr` | TODO | TODO |
| 8 | `ufw enable` | TODO | TODO |
| 9 | `ufw allow` | TODO | TODO |
| 10 | `ufw status` | TODO | TODO |

## Day 10: Security Checkpoint & Audit

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `find / -perm /4000 (SUID audit)` | TODO | TODO |
| 2 | `last` | TODO | TODO |
| 3 | `lastlog` | TODO | TODO |
| 4 | `w` | TODO | TODO |
| 5 | `who` | TODO | TODO |
| 6 | `groups` | TODO | TODO |
| 7 | `passwd` | TODO | TODO |
| 8 | `chage -l` | TODO | TODO |
| 9 | `lastb` | TODO | TODO |
| 10 | `history \| grep sudo` | TODO | TODO |

## Day 11: Creating & Managing Users

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `useradd` | TODO | TODO |
| 2 | `useradd -m` | TODO | TODO |
| 3 | `useradd -m -s` | TODO | TODO |
| 4 | `adduser` | TODO | TODO |
| 5 | `passwd` | TODO | TODO |
| 6 | `usermod -aG` | TODO | TODO |
| 7 | `usermod -s` | TODO | TODO |
| 8 | `usermod -l` | TODO | TODO |
| 9 | `userdel` | TODO | TODO |
| 10 | `userdel -r` | TODO | TODO |

## Day 12: Groups & Access Circles

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `groupadd` | TODO | TODO |
| 2 | `groupdel` | TODO | TODO |
| 3 | `gpasswd -a` | TODO | TODO |
| 4 | `gpasswd -d` | TODO | TODO |
| 5 | `getent group` | TODO | TODO |
| 6 | `getent passwd` | TODO | TODO |
| 7 | `groups` | TODO | TODO |
| 8 | `id -Gn` | TODO | TODO |
| 9 | `newgrp` | TODO | TODO |
| 10 | `cat /etc/group` | TODO | TODO |

## Day 13: APT Package Management (Debian/Ubuntu)

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `apt update` | TODO | TODO |
| 2 | `apt upgrade` | TODO | TODO |
| 3 | `apt full-upgrade` | TODO | TODO |
| 4 | `apt install` | TODO | TODO |
| 5 | `apt remove` | TODO | TODO |
| 6 | `apt purge` | TODO | TODO |
| 7 | `apt autoremove` | TODO | TODO |
| 8 | `apt search` | TODO | TODO |
| 9 | `apt show` | TODO | TODO |
| 10 | `dpkg -l / dpkg -L` | TODO | TODO |

## Day 14: DNF/YUM & Alternative Installs

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `dnf update` | TODO | TODO |
| 2 | `dnf install` | TODO | TODO |
| 3 | `dnf remove` | TODO | TODO |
| 4 | `dnf search` | TODO | TODO |
| 5 | `yum install` | TODO | TODO |
| 6 | `rpm -qa` | TODO | TODO |
| 7 | `snap install` | TODO | TODO |
| 8 | `add-apt-repository` | TODO | TODO |
| 9 | `dpkg -i` | TODO | TODO |
| 10 | `pip / npm install` | TODO | TODO |

## Day 15: Users & Packages Checkpoint

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `id <user>` | TODO | TODO |
| 2 | `getent passwd <user>` | TODO | TODO |
| 3 | `useradd -m -G` | TODO | TODO |
| 4 | `passwd <user>` | TODO | TODO |
| 5 | `apt list --installed` | TODO | TODO |
| 6 | `apt list --upgradable` | TODO | TODO |
| 7 | `apt update && apt install -y` | TODO | TODO |
| 8 | `dpkg -l \| grep` | TODO | TODO |
| 9 | `apt autoremove` | TODO | TODO |
| 10 | `history` | TODO | TODO |

## Day 16: Environment Variables

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `printenv` | TODO | TODO |
| 2 | `printenv HOME` | TODO | TODO |
| 3 | `echo $VAR` | TODO | TODO |
| 4 | `export` | TODO | TODO |
| 5 | `unset` | TODO | TODO |
| 6 | `env` | TODO | TODO |
| 7 | `source` | TODO | TODO |
| 8 | `echo $PATH` | TODO | TODO |
| 9 | `export PATH=$PATH:` | TODO | TODO |
| 10 | `cat /etc/environment` | TODO | TODO |

## Day 17: Persisting Configuration

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `nano ~/.bashrc` | TODO | TODO |
| 2 | `source ~/.bashrc` | TODO | TODO |
| 3 | `cat ~/.bash_profile` | TODO | TODO |
| 4 | `sudo nano /etc/environment` | TODO | TODO |
| 5 | `sudo nano /etc/bash.bashrc` | TODO | TODO |
| 6 | `alias` | TODO | TODO |
| 7 | `unalias` | TODO | TODO |
| 8 | `type` | TODO | TODO |
| 9 | `which` | TODO | TODO |
| 10 | `whereis` | TODO | TODO |

## Day 18: Vim Fundamentals

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `vim <file>` | TODO | TODO |
| 2 | `i (insert mode)` | TODO | TODO |
| 3 | `Esc (command mode)` | TODO | TODO |
| 4 | `:w` | TODO | TODO |
| 5 | `:q` | TODO | TODO |
| 6 | `:wq / :x` | TODO | TODO |
| 7 | `:q!` | TODO | TODO |
| 8 | `dd` | TODO | TODO |
| 9 | `yy / p` | TODO | TODO |
| 10 | `u / Ctrl+r` | TODO | TODO |

## Day 19: Vim Navigation & Search/Replace

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `gg / G` | TODO | TODO |
| 2 | `:10 (go to line)` | TODO | TODO |
| 3 | `/ (search forward)` | TODO | TODO |
| 4 | `? (search backward)` | TODO | TODO |
| 5 | `n / N` | TODO | TODO |
| 6 | `:%s/old/new/g` | TODO | TODO |
| 7 | `dw` | TODO | TODO |
| 8 | `x` | TODO | TODO |
| 9 | `o / O` | TODO | TODO |
| 10 | `ZZ` | TODO | TODO |

## Day 20: Text Processing & Pipes

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `grep` | TODO | TODO |
| 2 | `grep -r` | TODO | TODO |
| 3 | `grep -i` | TODO | TODO |
| 4 | `sort` | TODO | TODO |
| 5 | `sort -n` | TODO | TODO |
| 6 | `uniq` | TODO | TODO |
| 7 | `cut -d',' -f` | TODO | TODO |
| 8 | `awk '{print $1}'` | TODO | TODO |
| 9 | `sed 's/old/new/g'` | TODO | TODO |
| 10 | `pipe chains (\|)` | TODO | TODO |

## Day 21: Viewing Processes

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `ps aux` | TODO | TODO |
| 2 | `ps -ef` | TODO | TODO |
| 3 | `ps -u` | TODO | TODO |
| 4 | `top` | TODO | TODO |
| 5 | `htop` | TODO | TODO |
| 6 | `pgrep` | TODO | TODO |
| 7 | `pstree` | TODO | TODO |
| 8 | `lsof -i` | TODO | TODO |
| 9 | `jobs` | TODO | TODO |
| 10 | `nice / renice` | TODO | TODO |

## Day 22: Controlling Processes with Signals

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `kill` | TODO | TODO |
| 2 | `kill -9` | TODO | TODO |
| 3 | `kill -HUP` | TODO | TODO |
| 4 | `killall` | TODO | TODO |
| 5 | `pkill` | TODO | TODO |
| 6 | `fg` | TODO | TODO |
| 7 | `bg` | TODO | TODO |
| 8 | `Ctrl+Z (suspend)` | TODO | TODO |
| 9 | `nohup` | TODO | TODO |
| 10 | `disown` | TODO | TODO |

## Day 23: Init Systems & systemctl Basics

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `systemctl start` | TODO | TODO |
| 2 | `systemctl stop` | TODO | TODO |
| 3 | `systemctl restart` | TODO | TODO |
| 4 | `systemctl reload` | TODO | TODO |
| 5 | `systemctl enable` | TODO | TODO |
| 6 | `systemctl disable` | TODO | TODO |
| 7 | `systemctl enable --now` | TODO | TODO |
| 8 | `systemctl status` | TODO | TODO |
| 9 | `systemctl is-active` | TODO | TODO |
| 10 | `systemctl is-enabled` | TODO | TODO |

## Day 24: Deeper Service Management & Logs

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `systemctl list-units --type=service` | TODO | TODO |
| 2 | `systemctl list-units --state=failed` | TODO | TODO |
| 3 | `systemctl daemon-reload` | TODO | TODO |
| 4 | `journalctl` | TODO | TODO |
| 5 | `journalctl -f` | TODO | TODO |
| 6 | `journalctl -u` | TODO | TODO |
| 7 | `journalctl --since` | TODO | TODO |
| 8 | `journalctl -p err` | TODO | TODO |
| 9 | `tail -f /var/log/syslog` | TODO | TODO |
| 10 | `tail -f /var/log/auth.log` | TODO | TODO |

## Day 25: Process & Service Checkpoint

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `ps aux \| grep` | TODO | TODO |
| 2 | `systemctl status <svc>` | TODO | TODO |
| 3 | `journalctl -u <svc> --since today` | TODO | TODO |
| 4 | `kill -0 (liveness check)` | TODO | TODO |
| 5 | `uptime` | TODO | TODO |
| 6 | `free -h` | TODO | TODO |
| 7 | `vmstat` | TODO | TODO |
| 8 | `iostat` | TODO | TODO |
| 9 | `watch` | TODO | TODO |
| 10 | `crontab -e / crontab -l` | TODO | TODO |

## Day 26: Networking Basics

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `ip a` | TODO | TODO |
| 2 | `ip route` | TODO | TODO |
| 3 | `ping -c` | TODO | TODO |
| 4 | `curl` | TODO | TODO |
| 5 | `curl -I` | TODO | TODO |
| 6 | `wget` | TODO | TODO |
| 7 | `netstat -tulnp` | TODO | TODO |
| 8 | `ss -tulnp` | TODO | TODO |
| 9 | `hostname` | TODO | TODO |
| 10 | `hostnamectl` | TODO | TODO |

## Day 27: Remote Access & File Transfer

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `ssh` | TODO | TODO |
| 2 | `ssh -p` | TODO | TODO |
| 3 | `ssh -i` | TODO | TODO |
| 4 | `ssh-keygen` | TODO | TODO |
| 5 | `ssh-copy-id` | TODO | TODO |
| 6 | `scp` | TODO | TODO |
| 7 | `sftp` | TODO | TODO |
| 8 | `rsync` | TODO | TODO |
| 9 | `~/.ssh/config` | TODO | TODO |
| 10 | `sshd_config hardening` | TODO | TODO |

## Day 28: Bash Scripting Foundations

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `#!/bin/bash (shebang)` | TODO | TODO |
| 2 | `chmod +x script.sh` | TODO | TODO |
| 3 | `./script.sh` | TODO | TODO |
| 4 | `VAR=value` | TODO | TODO |
| 5 | `$() command substitution` | TODO | TODO |
| 6 | `read -p` | TODO | TODO |
| 7 | `if / elif / else / fi` | TODO | TODO |
| 8 | `-gt / -lt / -eq` | TODO | TODO |
| 9 | `for loop` | TODO | TODO |
| 10 | `while loop` | TODO | TODO |

## Day 29: Functions, Arguments & Automation

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `function_name() { }` | TODO | TODO |
| 2 | `$1 / $2 positional args` | TODO | TODO |
| 3 | `$# / $* / $@` | TODO | TODO |
| 4 | `$0` | TODO | TODO |
| 5 | `exit codes ($?)` | TODO | TODO |
| 6 | `crontab syntax` | TODO | TODO |
| 7 | `cron scheduling (0 * * * *)` | TODO | TODO |
| 8 | `nohup script.sh &` | TODO | TODO |
| 9 | `trap` | TODO | TODO |
| 10 | `logger` | TODO | TODO |

## Day 30: Capstone: Full System Command Mastery Review

| # | Command | What it does (my words) | Surprise or mistake |
|---|---------|-------------------------|---------------------|
| 1 | `Build a full system health-check script` | TODO | TODO |
| 2 | `Combine ps + systemctl + journalctl in one report` | TODO | TODO |
| 3 | `SSH into a remote host and run a command` | TODO | TODO |
| 4 | `scp a file as part of a deployment` | TODO | TODO |
| 5 | `Apply chmod/chown to deployed files` | TODO | TODO |
| 6 | `Schedule the health check with cron` | TODO | TODO |
| 7 | `Parse logs with grep, awk, and sed` | TODO | TODO |
| 8 | `Use find to clean up stale files` | TODO | TODO |
| 9 | `Run a security audit (last, who, history)` | TODO | TODO |
| 10 | `Present the 300-command journal for review` | TODO | TODO |

