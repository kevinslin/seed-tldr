---
id: windows.reg-restore
title: Reg Restore
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
# reg restore

> Restore a key and its values from a backup file.
> See `reg-save` for more information.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-restore>.

- Overwrite a specified key with data from a backup file:

`reg restore {{key_name}} {{path/to/file}}`

