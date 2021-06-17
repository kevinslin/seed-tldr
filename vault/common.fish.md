---
id: common.fish
title: Fish
desc: ''
updated: 1623965016124
created: 1623965016124
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fish

> The Friendly Interactive SHell, a command-line interpreter designed to be user friendly.
> More information: <https://fishshell.com>.

- Start an interactive shell session:

`fish`

- Execute a command and then exit:

`fish -c "{{command}}"`

- Execute a script:

`fish {{path/to/script.fish}}`

- Check a script for syntax errors:

`fish --no-execute {{path/to/script.fish}}`

- Start an interactive shell session in private mode, where the shell does not access old history or save new history:

`fish --private`

- Display version information and exit:

`fish --version`

- Set and export environmental variables that persist across shell restarts (from within the shell only):

`set -Ux {{variable_name}} {{variable_value}}`

