---
id: common.apropos
title: Apropos
desc: ''
updated: 1623965016112
created: 1623965016112
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apropos

> Search the manual pages for names and descriptions.
> More information: <https://manned.org/apropos>.

- Search for a keyword using a regular expression:

`apropos {{regular_expression}}`

- Search without restricting the output to the terminal width:

`apropos -l {{regular_expression}}`

- Search for pages that contain all of the expressions given:

`apropos {{regular_expression_1}} -a {{regular_expression_2}} -a {{regular_expression_3}}`

