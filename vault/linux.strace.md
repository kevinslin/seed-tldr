---
id: linux.strace
title: Strace
desc: ''
updated: 1623965016169
created: 1623965016169
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# strace

> Troubleshooting tool for tracing system calls.

- Start tracing a specific process by its PID:

`strace -p {{pid}}`

- Trace a process and filter output by system call:

`strace -p {{pid}} -e {{system_call_name}}`

- Count time, calls, and errors for each system call and report a summary on program exit:

`strace -p {{pid}} -c`

- Show the time spent in every system call:

`strace -p {{pid}} -T`

- Start tracing a program by executing it:

`strace {{program}}`

- Start tracing file operations of a program:

`strace -e trace=file {{program}}`

