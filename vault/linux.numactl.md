---
id: linux.numactl
title: Numactl
desc: ''
updated: 1623965016166
created: 1623965016166
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# numactl

> Control NUMA policy for processes or shared memory.
> More information: <https://man7.org/linux/man-pages/man8/numactl.8.html>.

- Run a command on node 0 with memory allocated on node 0 and 1:

`numactl --cpunodebind={{0}} --membind={{0,1}} -- {{command}} {{command_arguments}}`

- Run a command on CPUs (cores) 0-4 and 8-12 of the current cpuset:

`numactl --physcpubind={{+0-4,8-12}} -- {{command}} {{command_arguments}}`

- Run a command with its memory interleaved on all CPUs:

`numactl --interleave={{all}} -- {{command}} {{command_arguments}}`

