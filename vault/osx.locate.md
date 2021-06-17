---
id: osx.locate
title: Locate
desc: ''
updated: 1623965306235
created: 1623965306235
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# locate

> Find filenames quickly.

- Look for pattern in the database. Note: the database is recomputed periodically (usually weekly or daily):

`locate {{pattern}}`

- Look for a file by its exact filename (a pattern containing no globbing characters is interpreted as `*pattern*`):

`locate */{{filename}}`

- Recompute the database. You need to do it if you want to find recently added files:

`sudo /usr/libexec/locate.updatedb`

