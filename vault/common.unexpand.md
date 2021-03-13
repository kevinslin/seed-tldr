---
id: common.unexpand
title: Unexpand
desc: ''
updated: 1615655543090
created: 1615655543090
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

