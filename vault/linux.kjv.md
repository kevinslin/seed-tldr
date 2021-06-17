---
id: linux.kjv
title: Kjv
desc: ''
updated: 1623965016163
created: 1623965016163
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kjv

> The word of God available right on your desktop.
> More information: <https://github.com/bontibon/kjv>.

- Display books:

`kjv -l`

- Open a specific book:

`kjv {{Genesis}}`

- Open a specific chapter of a book:

`kjv {{Genesis}} {{2}}`

- Open a specific verse of a specific chapter of a book:

`kjv {{John}} {{3}}:{{16}}`

- Open a specific range of verses of a book's chapter:

`kjv {{Proverbs}} {{3}}:{{1-6}}`

- Display a specific range of verses of a book from different chapters:

`kjv {{Matthew}} {{1}}:{{7}}-{{2}}:{{6}}`

- Display all verses that match a pattern:

`kjv /{{Plagues}}`

- Display all verses that match a pattern in a specific book:

`kjv {{1Jn}}/{{antichrist}}`

