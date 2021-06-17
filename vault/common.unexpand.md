---
id: common.unexpand
title: Unexpand
desc: ''
updated: 1623965306214
created: 1623965306214
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unexpand

> Convert spaces to tabs.
> More information: <https://www.gnu.org/software/coreutils/unexpand>.

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

