---
id: common.touch
title: Touch
desc: ''
updated: 1623965016153
created: 1623965016153
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# touch

> Change a file access and modification times (atime, mtime).
> More information: <https://www.gnu.org/software/coreutils/touch>.

- Create a new empty file(s) or change the times for existing file(s) to current time:

`touch {{filename}}`

- Set the times on a file to a specific date and time:

`touch -t {{YYYYMMDDHHMM.SS}} {{filename}}`

- Use the times from a file to set the times on a second file:

`touch -r {{filename}} {{filename2}}`

- Create multiple files:

`touch {{file{1,2,3}.txt}}`

