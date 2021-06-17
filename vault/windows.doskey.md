---
id: windows.doskey
title: Doskey
desc: ''
updated: 1623965016176
created: 1623965016176
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# doskey

> Manage macros, windows commands and command-lines.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/doskey>.

- List available macros:

`doskey /macros`

- Create a new macro:

`doskey {{name}} = "{{command}}"`

- Create a new macro for a specific executable:

`doskey /exename={{executable}} {{name}} = "{{command}}"`

- Remove a macro:

`doskey {{name}} =`

- Display all commands that are stored in memory:

`doskey /history`

- Save macros to a file for portability:

`doskey /macros > {{macinit}}`

- Load macros from a file:

`doskey /macrofile = {{macinit}}`

