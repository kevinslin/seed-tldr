---
id: common.lldb
title: Lldb
desc: ''
updated: 1623965016135
created: 1623965016135
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lldb

> The LLVM Low-Level Debugger.
> More information: <https://lldb.llvm.org>.

- Debug an executable:

`lldb {{executable}}`

- Attach `lldb` to a running process with a given PID:

`lldb -p {{pid}}`

- Wait for a new process to launch with a given name, and attach to it:

`lldb -w -n {{process_name}}`

