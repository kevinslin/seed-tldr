---
id: linux.aspell
title: Aspell
desc: ''
updated: 1623965306219
created: 1623965306219
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

