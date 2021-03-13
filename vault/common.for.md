---
id: common.for
title: For
desc: ''
updated: 1615663978710
created: 1615663978710
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# for

> Shell loop over parameters.

- Perform a command with different arguments:

`for argument in 1 2 3; do {{command $argument}}; done`

- Perform a command in every directory:

`for d in *; do (cd $d; {{command}}); done`

