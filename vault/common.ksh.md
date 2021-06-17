---
id: common.ksh
title: Ksh
desc: ''
updated: 1623965306194
created: 1623965306194
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ksh

> Korn Shell, a Bash-compatible command-line interpreter.
> See also `histexpand` for history expansion.
> More information: <http://kornshell.com>.

- Start an interactive shell session:

`ksh`

- Execute a command and then exit:

`ksh -c "{{command}}"`

- Execute a script:

`ksh {{path/to/script.ksh}}`

- Execute a script, printing each command before executing it:

`ksh -x {{path/to/script.ksh}}`

