---
id: osx.mas
title: Mas
desc: ''
updated: 1623965016174
created: 1623965016174
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mas

> Command-line interface for the Mac App Store.
> More information: <https://github.com/mas-cli/mas>.

- Sign into the Mac App Store for the first time:

`mas signin {{user@example.com}}`

- Show all installed applications and their product identifiers:

`mas list`

- Search for an application, displaying the price alongside the results:

`mas search {{application}} --price`

- Install or update an application:

`mas install {{product_identifier}}`

- Install all pending updates:

`mas upgrade`

