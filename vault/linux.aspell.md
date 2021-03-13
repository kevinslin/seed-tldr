---
id: linux.aspell
title: Aspell
desc: ''
updated: 1615655543095
created: 1615655543095
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# aspell

> Interactive spell checker.

- Spell check a single file:

`aspell check {{path/to/file}}`

- List misspelled words from standard input:

`cat {{file}} | aspell list`

- Show available dictionary languages:

`aspell dicts`

- Run aspell with different language (takes two letter ISO 639 language code):

`aspell --lang={{cs}}`

- List misspelled words from standard input and ignore words from personal word list:

`cat {{file}} | aspell --personal={{personal-word-list.pws}} {{list}}`

