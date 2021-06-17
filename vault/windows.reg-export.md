---
id: windows.reg-export
title: Reg Export
desc: ''
updated: 1623965306238
created: 1623965306238
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# reg export

> Export the specified sub keys and values into a file.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-export>.

- Export all sub keys and values of a specific key:

`reg export {{key_name}} {{path/to/file.reg}}`

- Force overwriting of an existing file without prompt:

`reg export {{key_name}} {{path/to/file.reg}} /y`

