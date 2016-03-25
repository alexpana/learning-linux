# Learning Linux

## TODO

### Commands
- sysctl
- less
- grep
- ps
- watch (runs a command periodically, showing the output fullscreen)
- ln (hard links vs soft links)
- dd (copies the standard input to the standard output)

### Special files
- `/dev/kmsg`
- `/dev/null` accepts and discards all input; produces no output (always returns an end-of-file indication on a read)
- `/dev/zero` accepts and discards all input; produces a continuous stream of NUL (zero value) bytes
- `/dev/full` produces a continuous stream of NUL (zero value) bytes when read, and returns a "disk full" message when written to
- `/dev/random` and `/dev/urandom` produce a variable-length stream of pseudo-random numbers.

### Other
- xorg / X11

## Useful resources
- TLDR man pages http://tldr-pages.github.io/
- The Linux Documentation Project (TLDP) http://www.tldp.org/
- Online Man Pages http://man7.org/linux/man-pages/
- Linux Insides https://github.com/0xAX/linux-insides
