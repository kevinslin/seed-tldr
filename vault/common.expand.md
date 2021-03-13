---
id: common.expand
title: Expand
desc: ''
updated: 1615663978708
created: 1615663978708
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# expand

> Convert tabs to spaces.

- Convert tabs in each file to spaces, writing to standard output:

`expand {{file}}`

- Convert tabs to spaces, reading from standard input:

`expand`

- Do not convert tabs after non blanks:

`expand -i {{file}}`

- Have tabs a certain number of characters apart, not 8:

`expand -t={{number}} {{file}}`

- Use a comma separated list of explicit tab positions:

`expand -t={{1,4,6}}`

