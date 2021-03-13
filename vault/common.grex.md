---
id: common.grex
title: Grex
desc: ''
updated: 1615655543061
created: 1615655543061
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# grex

> Simple command line tool to generate regular expressions.
> More information: <https://github.com/pemistahl/grex>.

- Generate a simple regular expression:

` grex {{space_separated_strings}}`

- Generate a case-insensitive regex:

`grex -i {{space_separated_strings}}`

- Replace digits with '\\d':

`grex -d {{space_separated_strings}}`

- Replace unicode word character with '\\w':

`grex -w {{space_separated_strings}}`

- Replace spaces with '\\s':

`grex -s {{space_separated_strings}}`

- Add {min, max} quantifier representation for repeating sub-strings:

`grex -r {{space_separated_strings}}`

