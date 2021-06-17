---
id: common.pgrep
title: Pgrep
desc: ''
updated: 1623965016142
created: 1623965016142
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pgrep

> Find or signal processes by name.
> More information: <https://www.man7.org/linux/man-pages/man1/pkill.1.html>.

- Return PIDs of any running processes with a matching command string:

`pgrep {{process_name}}`

- Search for processes including their command-line options:

`pgrep --full "{{process_name}} {{parameter}}"`

- Search for processes run by a specific user:

`pgrep --euid root {{process_name}}`

