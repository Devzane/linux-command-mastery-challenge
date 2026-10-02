# Day 01: Where Am I? Basic Orientation - Commands

## 1. `pwd`

**Syntax:** `pwd`

**In my own words:** This is the first thing I check when I open a terminal. It tells me the present working directory — basically, where I am right now in the filesystem. It is short for "Print Working Directory."

## 2. `ls`

**Syntax:** `ls [path]`

**In my own words:** I use this to list what is inside a folder. If I just type `ls` on its own, it shows me the files and directories in the current location, laid out across multiple columns to save space on screen.

## 3. `ls -l`

**Syntax:** `ls -l [path]`

**In my own words:** The `-l` flag switches the listing to "long format." Instead of just names, I now see extra columns showing the file type, permissions, owner, size, and the date it was last modified.

## 4. `ls -a`

**Syntax:** `ls -a [path]`

**In my own words:** The `-a` flag makes `ls` show all files, including the hidden ones. Hidden files on Linux start with a dot, so without `-a` I would never even see them.

## 5. `ls -la`

**Syntax:** `ls -la [path]`

**In my own words:** This combines `-l` and `-a` together. I get the long-format columns and every hidden file revealed at the same time. I just stick both letters together after the dash.

## 6. `ls -lh`

**Syntax:** `ls -lh [path]`

**In my own words:** The `-h` flag makes the sizes human-readable. Instead of seeing a number like `4300`, I see something like `4.3K` or `2.9M`. Much easier to understand at a glance.

## 7. `cd (absolute path)`

**Syntax:** `cd /path/to/directory`

**In my own words:** `cd` stands for "change directory." When I give it a full absolute path that starts from `/`, it takes me straight to that location no matter where I currently am.

## 8. `cd ..`

**Syntax:** `cd ..`

**In my own words:** The two dots mean "one step back." If I am in `/var/log`, running `cd ..` takes me up to `/var`. It moves me one level up in the directory tree.

## 9. `cd ~`

**Syntax:** `cd ~`

**In my own words:** The tilde (`~`) is a shortcut for my home directory. No matter how deep in the filesystem I go, `cd ~` brings me straight back home in one shot.

## 10. `cd -`

**Syntax:** `cd -`

**In my own words:** The dash makes `cd` jump back to the last directory I was in. So if I was in `/var/log`, went home, and then typed `cd -`, I would be back in `/var/log`. It is like a toggle between two locations.
