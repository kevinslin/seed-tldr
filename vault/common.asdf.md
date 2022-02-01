---
id: common.asdf
title: Asdf
desc: ''
updated: 1642441814995
created: 1642441814995
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# asdf

> Command-line interface for managing versions of different packages.
> More information: <https://asdf-vm.com>.

- List all available plugins:

`asdf plugin-list-all`

- Install a plugin:

`asdf plugin-add {{name}}`

- List all available versions for a package:

`asdf list-all {{name}}`

- Install a specific version of a package:

`asdf install {{name}} {{version}}`

- Set global version for a package:

`asdf global {{name}} {{version}}`

- Set local version for a package:

`asdf local {{name}} {{version}}`

