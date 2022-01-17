---
id: linux.cgexec
title: Cgexec
desc: ''
updated: 1642441815090
created: 1642441815090
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cgexec

> Limit, measure, and control resources used by processes.
> Multiple cgroup types (aka controllers) exist, such as `cpu`, `memory`, etc.
> More information: <https://manned.org/cgexec>.

- Execute a process in a given cgroup with given controller:

`cgexec -g {{controller}}:{{cgroup_name}} {{process_name}}`

