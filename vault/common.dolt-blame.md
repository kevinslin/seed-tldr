---
id: common.dolt-blame
title: Dolt Blame
desc: ''
updated: 1623965306180
created: 1623965306180
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dolt blame

> Displays commit information for each row of a Dolt table.
> More information: <http://github.com/dolthub/dolt>.

- Display the latest commit for each row of a table:

`dolt blame {{table}}`

- Display the latest commits for each row of a table when the specified commit was made:

`dolt blame {{commit}} {{table}}`

- View help:

`dolt blame --help`

