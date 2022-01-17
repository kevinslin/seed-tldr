---
id: common.zsh
title: Zsh
desc: ''
updated: 1642441815086
created: 1642441815086
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zsh

> Z SHell, a Bash-compatible command-line interpreter.
> See also `histexpand` for history expansion.
> More information: <https://www.zsh.org>.

- Start an interactive shell session:

`zsh`

- Execute a command and then exit:

`zsh -c "{{command}}"`

- Execute a script:

`zsh {{path/to/script.zsh}}`

- Execute a script, printing each command before executing it:

`zsh --xtrace {{path/to/script.zsh}}`

- Start an interactive shell session in verbose mode, printing each command before executing it:

`zsh --verbose`

