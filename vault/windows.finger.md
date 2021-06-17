---
id: windows.finger
title: Finger
desc: ''
updated: 1623965306237
created: 1623965306237
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# finger

> Return information about one or more users on a specified system.
> The remote system must be running the Finger service.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/finger>.

- Display information about a specific user:

`finger {{user}}@{{host}}`

- Display information about all users on the specified host:

`finger @{{host}}`

- Display information in a longer format:

`finger {{user}}@{{host}} -l`

- Display help information:

`finger /?`

