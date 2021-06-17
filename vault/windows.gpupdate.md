---
id: windows.gpupdate
title: Gpupdate
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
# gpupdate

> A tool to check and apply Windows Group Policy settings.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/gpupdate>.

- Check and apply updated Group Policy settings:

`gpupdate`

- Specify the target Group Policy settings to check for update:

`gpupdate /target=:{{computer|user}}`

- Force all Group Policy settings to be reapplied:

`gpupdate /force`

- Display detailed usage information:

`gpupdate /?`

