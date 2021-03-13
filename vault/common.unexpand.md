---
id: common.unexpand
title: Unexpand
desc: ''
updated: 1615663978737
created: 1615663978737
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unexpand

> Convert spaces to tabs.

- Convert blanks in each file to tabs, writing to standard output:

`unexpand {{file}}`

- Convert blanks to tabs, reading from standard output:

`unexpand`

- Convert all blanks, instead of just initial blanks:

`unexpand -a {{file}}`

- Convert only leading sequences of blanks (overrides -a):

`unexpand --first-only {{file}}`

- Have tabs a certain number of characters apart, not 8 (enables -a):

`unexpand -t {{number}} {{file}}`

