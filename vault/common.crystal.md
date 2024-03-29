---
id: common.crystal
title: Crystal
desc: ''
updated: 1642441815005
created: 1642441815005
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# crystal

> Tool for managing Crystal source code.
> More information: <https://crystal-lang.org/reference/using_the_compiler>.

- Run a Crystal file:

`crystal {{path/to/file.cr}}`

- Compile a file and all dependencies to a single executable:

`crystal build {{path/to/file.cr}}`

- Start a local interactive server for testing the language:

`crystal play`

- Create a project directory for a Crystal application:

`crystal init app {{application_name}}`

- Display all help options:

`crystal help`

