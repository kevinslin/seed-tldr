---
id: osx.pwgen
title: Pwgen
desc: ''
updated: 1615663978760
created: 1615663978760
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pwgen

> Generate pronounceable passwords.

- Generate random password with s[y]mbols:

`pwgen -y {{length}}`

- Generate secure, hard-to-memorize passwords:

`pwgen -s {{length}}`

- Generate password with at least one capital letter in them:

`pwgen -c {{length}}`
