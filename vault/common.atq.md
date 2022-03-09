---
id: common.atq
title: Atq
desc: ''
updated: 1646802118602
created: 1646802118602
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# atq

> Show jobs scheduled by `at` or `batch` commands.
> More information: <https://manned.org/atq>.

- Show the current user's scheduled jobs:

`atq`

- Show jobs from queue named 'a' (queues have single-character names):

`atq -q {{a}}`

- Show jobs of all users (run as superuser):

`sudo atq`

