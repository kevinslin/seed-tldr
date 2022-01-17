---
id: common.stack
title: Stack
desc: ''
updated: 1642441815071
created: 1642441815071
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stack

> Tool for managing Haskell projects.
> More information: <https://github.com/commercialhaskell/stack>.

- Create a new package:

`stack new {{package_name}} {{template_name}}`

- Compile a package:

`stack build`

- Run tests inside a package:

`stack test`

- Compile a project and re-compile every time a file changes:

`stack build --file-watch`

- Compile a project and execute a command after compilation:

`stack build --exec "{{command}}"`

- Run a program and pass an argument to it:

`stack exec {{program_name}} -- {{argument}}`

