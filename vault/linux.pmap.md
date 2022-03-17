---
id: linux.pmap
title: Pmap
desc: ''
updated: 1647518525214
created: 1647518525214
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pmap

> Report memory map of a process or processes.
> More information: <https://manned.org/pmap>.

- Print memory map for a specific process id (PID):

`pmap {{pid}}`

- Show the extended format:

`pmap --extended {{pid}}`

- Show the device format:

`pmap --device {{pid}}`

- Limit results to a memory address range specified by `low` and `high`:

`pmap --range {{low}},{{high}}`

- Print memory maps for multiple processes:

`pmap {{pid1 pid2 ...}}`

