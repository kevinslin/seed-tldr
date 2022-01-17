---
id: common.py-spy
title: Py Spy
desc: ''
updated: 1642441815063
created: 1642441815063
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# py-spy

> A sampling profiler for Python programs.
> More information: <https://github.com/benfred/py-spy>.

- Show a live view of the functions that take the most execution time of a running process:

`py-spy top --pid {{pid}}`

- Start a program and show a live view of the functions that take the most execution time:

`py-spy top -- python {{path/to/file.py}}`

- Produce an SVG flame graph of the function call execution time:

`py-spy record -o {{path/to/profile.svg}} --pid {{pid}}`

- Dump the call stack of a running process:

`py-spy dump --pid {{pid}}`

