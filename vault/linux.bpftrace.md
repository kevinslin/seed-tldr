---
id: linux.bpftrace
title: Bpftrace
desc: ''
updated: 1642441815089
created: 1642441815089
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bpftrace

> High-level tracing language for Linux eBPF.
> More information: <https://github.com/iovisor/bpftrace>.

- Display bpftrace version:

`bpftrace -V`

- List all available probes:

`sudo bpftrace -l`

- Run a one-liner program (e.g. syscall count by program):

`sudo bpftrace -e '{{tracepoint:raw_syscalls:sys_enter { @[comm] = count(); }}}'`

- Run a program from a file:

`sudo bpftrace {{path/to/file}}`

- Trace a program by PID:

`sudo bpftrace -e '{{tracepoint:raw_syscalls:sys_enter /pid == 123/ { @[comm] = count(); }}}'`

- Do a dry run and display the output in eBPF format:

`sudo bpftrace -d -e '{{one_line_program}}'`

