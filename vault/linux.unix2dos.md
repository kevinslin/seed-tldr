---
id: linux.unix2dos
title: Unix2dos
desc: ''
updated: 1615663978757
created: 1615663978757
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unix2dos

> Change Unix-style line endings to DOS-style.
> Replaces CR with CRLF.

- Change the line endings of a file:

`unix2dos {{filename}}`

- Create a copy with DOS-style line endings:

`unix2dos -n {{filename}} {{new_filename}}`

