---
id: sunos.truss
title: Truss
desc: ''
updated: 1615663978762
created: 1615663978762
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# truss

> Troubleshooting tool for tracing system calls.
> SunOS equivalent of strace.

- Start tracing a program by executing it, following all child processes:

`truss -f {{program}}`

- Start tracing a specific process by its PID:

`truss -p {{pid}}`

- Start tracing a program by executing it, showing arguments and environment variables:

`truss -a -e {{program}}`

- Count time, calls, and errors for each system call and report a summary on program exit:

`truss -c -p {{pid}}`

- Trace a process filtering output by system call:

`truss -p {{pid}} -t {{system_call_name}}`

