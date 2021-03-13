---
id: linux.runsv
title: Runsv
desc: ''
updated: 1615663978755
created: 1615663978755
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# runsv

> Start and manage a runit service.

- Start a runit service as the current user:

`runsv {{path/to/service}}`

- Start a runit service as root:

`sudo runsv {{path/to/service}}`

