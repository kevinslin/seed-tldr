---
id: common.hg-status
title: Hg Status
desc: ''
updated: 1615663978718
created: 1615663978718
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hg status

> Show files that have changed in the working directory.
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#status>.

- Display the status of changed files:

`hg status`

- Display only modified files:

`hg status --modified`

- Display only added files:

`hg status --added`

- Display only removed files:

`hg status --removed`

- Display only deleted (but tracked) files:

`hg status --deleted`

- Display changes in the working directory compared to a specified changeset:

`hg status --rev {{revision}}`

- Display only files matching a specified glob pattern:

`hg status --include {{pattern}}`

- Display files, excluding those that match a specified glob pattern:

`hg status --exclude {{pattern}}`

