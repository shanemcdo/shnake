# Shnake

A basic snake game written in POSIX-compliant shell.

To run you can paste `sh -c "$(curl https://shanemcd.net/shnake/)"` into any UNIX terminal.
The controls are
<kbd>w</kbd>
<kbd>a</kbd>
<kbd>s</kbd>
<kbd>d</kbd>
for movement and
<kbd>q</kbd>
to quit.

On some systems using `bash` instead of `sh` is required.

## Github Pages

`index.html` is a symbolic link to the `shnake` script so we can curl from the github pages site directly
instead of the much longer `https://raw.githubusercontent.com/shanemcdo/shnake/main/shnake` url.

## Known Issues

- `$RANDOM` is undefined for dash
- `head -c1` may not be defined on some systems
- `clear` is not guarenteed by POSIX
