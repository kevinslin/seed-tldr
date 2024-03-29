---
id: common.ssh-agent
title: Ssh Agent
desc: ''
updated: 1642441815070
created: 1642441815070
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ssh-agent

> Spawn an SSH Agent process.
> An SSH Agent holds SSH keys decrypted in memory until removed or the process is killed.
> See also `ssh-add`, which can add and manage keys held by an SSH Agent.
> More information: <https://man.openbsd.org/ssh-agent>.

- Start an SSH Agent for the current shell:

`eval $(ssh-agent)`

- Kill the currently running agent:

`ssh-agent -k`

