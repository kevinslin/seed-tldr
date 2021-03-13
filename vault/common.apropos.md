---
id: common.apropos
title: Apropos
desc: ''
updated: 1615663978698
created: 1615663978698
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apropos

> Search in manpages, for example to find a new command.

- Search for keyword:

`apropos {{regular_expression}}`

- Search without restricting output to terminal width:

`apropos -l {{regular_expression}}`

- Search for pages that only contain all of the expressions given (AND search):

`apropos {{regular_expression_1}} -a {{regular_expression_2}} -a {{regular_expression_3}`

