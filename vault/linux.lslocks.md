---
id: linux.lslocks
title: Lslocks
desc: ''
updated: 1623965016164
created: 1623965016164
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lslocks

> List local system locks.

- List all local system locks:

`lslocks`

- List locks with defined column headers:

`lslocks --output {{PID}},{{COMMAND}},{{PATH}}`

- List locks producing a raw output (no columns), and without column headers:

`lslocks --raw --noheadings`

- List locks by PID input:

`lslocks --pid {{PID}}`

- List locks with json output to stdout:

`lslocks --json`

