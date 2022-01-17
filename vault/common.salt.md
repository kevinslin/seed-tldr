---
id: common.salt
title: Salt
desc: ''
updated: 1642441815067
created: 1642441815067
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# salt

> Execute commands and assert state on remote salt minions.
> More information: <https://docs.saltstack.com/ref/cli/salt.html>.

- List connected minions:

`salt '*' test.ping`

- Execute a highstate on all connected minions:

`salt '*' state.highstate`

- Upgrade packages using the OS package manager (apt, yum, brew) on a subset of minions:

`salt '*.example.com' pkg.upgrade`

- Execute an arbitrary command on a particular minion:

`salt '{{minion_id}}' cmd.run "ls "`

