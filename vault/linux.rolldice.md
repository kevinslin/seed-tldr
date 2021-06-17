---
id: linux.rolldice
title: Rolldice
desc: ''
updated: 1623965306228
created: 1623965306228
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rolldice

> Roll virtual dice.
> More information: <https://manned.org/rolldice>.

- Roll a single 20 sided dice:

`rolldice d{{20}}`

- Roll two six sided dice and drop the lowest roll:

`rolldice {{2}}d{{6}}s{{1}}`

- Roll two 20 sided dice and add a modifier value:

`rolldice {{2}}d{{20}}{{+5}}`

- Roll a 20 sided dice two times:

`rolldice {{2}}xd{{20}}`

