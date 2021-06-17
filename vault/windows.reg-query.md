---
id: windows.reg-query
title: Reg Query
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
# reg query

> Display the values of keys and sub keys in the registry.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-query>.

- Display all values of a key:

`reg query {{key_name}}`

- Display a specific value of a key:

`reg query {{key_name}} /v {{value}}`

- Display all values of a key and its sub keys:

`reg query {{key_name}} /s`

- Search for keys and values matching a specific pattern:

`reg query {{key_name}} /f "{{query_pattern}}"`

- Display a value of a key matching a specified data type:

`reg query {{key_name}} /t {{type}}`

