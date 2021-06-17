---
id: common.runsv
title: Runsv
desc: ''
updated: 1623965306208
created: 1623965306208
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# runsv

> Start and manage a runit service.
> More information: <https://manpages.ubuntu.com/manpages/latest/man8/runsv.8.html>.

- Start a runit service as the current user:

`runsv {{path/to/service}}`

- Start a runit service as root:

`sudo runsv {{path/to/service}}`

