---
id: common.fish
title: Fish
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
# fish

> The Friendly Interactive SHell, a command-line interpreter designed to be user friendly.
> More information: <https://fishshell.com>.

- Start an interactive shell session:

`fish`

- Start an interactive shell session without loading startup configs:

`fish --no-config`

- Execute a command:

`fish --command "{{command}}"`

- Execute a script:

`fish {{path/to/script.fish}}`

- Check a script for syntax errors:

`fish --no-execute {{path/to/script.fish}}`

- Start an interactive shell session in private mode, where the shell does not access old history or save new history:

`fish --private`

- Define and export an environmental variable that persists across shell restarts (builtin):

`set --universal --export {{variable_name}} {{variable_value}}`

- Print the version:

`fish --version`

