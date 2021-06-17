---
id: linux.taskset
title: Taskset
desc: ''
updated: 1623965016169
created: 1623965016169
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# taskset

> Get or set a process' CPU affinity or start a new process with a defined CPU affinity.

- Get a running process' CPU affinity by PID:

`taskset --pid --cpu-list {{pid}}`

- Set a running process' CPU affinity by PID:

`taskset --pid --cpu-list {{cpu_id}} {{pid}}`

- Start a new process with affinity for a single CPU:

`taskset --cpu-list {{cpu_id}} {{command}}`

- Start a new process with affinity for multiple non-sequential CPUs:

`taskset --cpu-list {{cpu_id_1}} {{cpu_id_2}} {{cpu_id_3}}`

- Start a new process with affinity for CPUs 1 through 4:

`taskset --cpu-list {{cpu_id_1}},{{cpu_id_4}}`

