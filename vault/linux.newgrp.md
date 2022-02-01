---
id: linux.newgrp
title: Newgrp
desc: ''
updated: 1642441815105
created: 1642441815105
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# newgrp

> Switch primary group membership.

- Change user's primary group membership:

`newgrp {{group_name}}`

- Reset primary group membership to user's default group in `/etc/passwd`:

`newgrp`

