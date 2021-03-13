---
id: common.htop
title: Htop
desc: ''
updated: 1615663978719
created: 1615663978719
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# htop

> Display dynamic real-time information about running processes. An enhanced version of `top`.

- Start htop:

`htop`

- Start htop displaying only processes owned by given user:

`htop -u {{username}}`

- Sort processes by a column (use `--sort-key help` for a column list):

`htop -s {{column_name}}`

- Get help about interactive commands:

`?`

