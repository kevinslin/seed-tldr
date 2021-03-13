---
id: linux.newgrp
title: Newgrp
desc: ''
updated: 1615663978751
created: 1615663978751
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

