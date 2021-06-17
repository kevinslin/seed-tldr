---
id: common.s
title: S
desc: ''
updated: 1623965016148
created: 1623965016148
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# s

> Web search from the terminal.

- Search for a query on Google(default provider):

`s {{query}}`

- List all providers:

`s --list-providers`

- Search for a query with a given provider:

`s --provider {{provider}} {{query}}`

- Use a specified binary to perform the search query:

`s --binary "{{binary}} {{arguments}}" {{query}}`

