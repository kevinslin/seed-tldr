---
id: linux.taskset
title: Taskset
desc: ''
updated: 1615655543110
created: 1615655543110
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

