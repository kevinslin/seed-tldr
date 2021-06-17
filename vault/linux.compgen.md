---
id: linux.compgen
title: Compgen
desc: ''
updated: 1623965306220
created: 1623965306220
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# compgen

> A built-in command for auto-completion in bash, which is called on pressing TAB key twice.

- List all commands that you could run:

`compgen -c`

- List all aliases:

`compgen -a`

- List all functions that you could run:

`compgen -A function`

- Show shell reserved key words:

`compgen -k`

- See all available commands/aliases starting with 'ls':

`compgen -ac {{ls}}`

