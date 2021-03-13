---
id: osx.pwgen
title: Pwgen
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pwgen

> Generate pronounceable passwords.

- Generate random password with s[y]mbols:

`pwgen -y {{length}}`

- Generate secure, hard-to-memorize passwords:

`pwgen -s {{length}}`

- Generate password with at least one capital letter in them:

`pwgen -c {{length}}`

