# Day 01: Where Am I? Basic Orientation

## Phase 1 - File Navigation & Filesystem Mastery | Day 1 of 30

## Commands covered today

See [commands.md](./commands.md) for all 10 commands with syntax and my own explanation of what each one does and when I would reach for it.

## What I practiced

I started by running `pwd` just to confirm where I was — I did not even know you could do that before. Then I explored `ls` in all its forms: plain `ls` to see the files, `ls -l` to see the long list with all the extra details like permissions and size, `ls -a` to reveal the hidden files that start with a dot, and `ls -lh` to make the sizes actually readable. After that, I moved around the filesystem using `cd`. I used an absolute path to jump to `/var/log`, then came back home with `cd ~`, and once I realized I needed to go back to `/var/log` again, I just typed `cd -` and it took me straight back. That toggle trick was the one that impressed me the most. Finally, I used `cd ..` to step back up through the directory tree one level at a time.

## What surprised me

I did not understand at first why `ls` was squashing so many files into the same row — I thought it was broken or cutting things off, but it turns out that is just how `ls` works by default: it fits as many names as it can into columns to save screen space. Once I used `ls -l`, everything spread out into its own line and it made sense.

## Evidence

Screenshot or terminal transcript of the drill in [evidence/](./evidence/).

## Related

Previous day: none (this is where it starts)
Next day: ../day-02-file-operations/
LinkedIn article: [Read the post](https://lnkd.in/p/dJEEJAJu)
