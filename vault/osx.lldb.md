---
id: osx.lldb
title: Lldb
desc: ''
updated: 1644840636309
created: 1644840636309
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lldb

> The LLVM Low-Level Debugger.
> More information: <https://lldb.llvm.org/man/lldb.html>.

- Debug an executable:

`lldb "{{executable}}"`

- Attach `lldb` to a running process with a given PID:

`lldb -p {{pid}}`

- Wait for a new process to launch with a given name, and attach to it:

`lldb -w -n "{{process_name}}"`

