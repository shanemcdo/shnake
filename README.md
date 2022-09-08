# Shnake

A basic snake game written in POSIX-compliant shell.

To run you can paste `sh -c "$(curl https://raw.githubusercontent.com/kermitpurple/shnake/main/shnake)"` into any good terminal.
The controls are
<kbd>w</kbd>
<kbd>a</kbd>
<kbd>s</kbd>
<kbd>d</kbd>
for movement and
<kbd>q</kbd>
to quit.

## Known Issues

- `$RANDOM` is undefined for dash
- `head -c1` may not be defined on some systems
- `clear` is not guarenteed by POSIX
