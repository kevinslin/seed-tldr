---
id: common.atq
title: Atq
desc: ''
updated: 1623965016113
created: 1623965016113
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# atq

> Show jobs scheduled by `at` or `batch` commands.
> More information: <https://man.archlinux.org/man/at.1>.

- Show the current user's scheduled jobs:

`atq`

- Show jobs from queue named 'a' (queues have single-character names):

`atq -q {{a}}`

- Show jobs of all users (run as super user):

`sudo atq`

