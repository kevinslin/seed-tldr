---
id: linux.qtchooser
title: Qtchooser
desc: ''
updated: 1623965306228
created: 1623965306228
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qtchooser

> A wrapper used to select between Qt development binary versions.
> More information: <https://manned.org/qtchooser>.

- List available Qt versions from the configuration files:

`qtchooser --list-versions`

- Print environment information:

`qtchooser --print-env`

- Run the specified tool using the specified Qt version:

`qtchooser --run-tool={{tool}} --qt={{version_name}}`

- Add a Qt version entry to be able to choose from:

`qtchooser --install {{version_name}} {{path/to/qmake}}`

- Display all available options:

`qtchooser --help`

