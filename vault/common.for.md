---
id: common.for
title: For
desc: ''
updated: 1642441815018
created: 1642441815018
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# for

> Shell loop over parameters.
> More information: <https://man.archlinux.org/man/for.n>.

- Perform a command with different arguments:

`for argument in 1 2 3; do {{command $argument}}; done`

- Perform a command in every directory:

`for d in *; do (cd $d; {{command}}); done`

