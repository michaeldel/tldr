# touch

> Change a file access and modification times (atime, mtime).
> More information: <https://man7.org/linux/man-pages/man1/touch.1.html>.

- Create a new empty file(s) or change the times for existing file(s) to current time:

`touch {{filename}}`

- Set the times on a file to a specific date and time:

`touch -t {{YYYYMMDDHHMM.SS}} {{filename}}`

- Use the times from a file to set the times on a second file:

`touch -r {{filename}} {{filename2}}`
