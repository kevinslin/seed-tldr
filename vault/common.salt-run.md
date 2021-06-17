---
id: common.salt-run
title: Salt Run
desc: ''
updated: 1623965016148
created: 1623965016148
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# salt-run

> Frontend for executing salt-runners on minions.
> More information: <https://docs.saltstack.com/ref/cli/salt-run.html>.

- Show status of all minions:

`salt-run manage.status`

- Show all minions which are disconnected:

`salt-run manage.up`

