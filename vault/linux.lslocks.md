---
id: linux.lslocks
title: Lslocks
desc: ''
updated: 1642441815102
created: 1642441815102
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lslocks

> List local system locks.
> More information: <https://manned.org/lslocks>.

- List all local system locks:

`lslocks`

- List locks with defined column headers:

`lslocks --output {{PID}},{{COMMAND}},{{PATH}}`

- List locks producing a raw output (no columns), and without column headers:

`lslocks --raw --noheadings`

- List locks by PID input:

`lslocks --pid {{PID}}`

- List locks with JSON output to stdout:

`lslocks --json`

