---
id: common.atq
title: Atq
desc: ''
updated: 1615663978699
created: 1615663978699
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# atq

> Show jobs scheduled by `at` or `batch` commands.

- Show the current user's scheduled jobs:

`atq`

- Show jobs from queue named 'a' (queues have single-character names):

`atq -q {{a}}`

- Show jobs of all users (run as super user):

`sudo atq`

