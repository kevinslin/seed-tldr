---
id: linux.chrt
title: Chrt
desc: ''
updated: 1623965016159
created: 1623965016159
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chrt

> Manipulate the real-time attributes of a process.
> More information: <https://man7.org/linux/man-pages/man1/chrt.1.html>.

- Display attributes of a process:

`chrt --pid {{PID}}`

- Display attributes of all threads of a process:

`chrt --all-tasks --pid {{PID}}`

- Display the min/max priority values that can be used with `chrt`:

`chrt --max`

- Set the scheduling policy for a process:

`chrt --pid {{PID}} --{{deadline|idle|batch|rr|fifo|other}}`

