---
id: common.swipl
title: Swipl
desc: ''
updated: 1642441815074
created: 1642441815074
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# swipl

> SWI-Prolog - A comprehensive free Prolog environment.
> More information: <https://www.swi-prolog.org/>.

- Start an interactive session:

`swipl`

- Execute a command without showing any output:

`swipl --quiet -t "{{command}}"`

- Execute a script:

`swipl {{path/to/file.pl}}`

- Print all shell configuration variables:

`swipl --dump-runtime-variables`

- Print the version:

`swipl --version`

