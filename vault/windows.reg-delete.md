---
id: windows.reg-delete
title: Reg Delete
desc: ''
updated: 1615663978764
created: 1615663978764
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# reg delete

> Delete keys or their values from the registry.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-delete>.

- Delete a specific registry key:

`reg delete {{key_name}}`

- Delete a value under a specific key:

`reg delete {{key_name}} /v {{value}}`

- Delete all values recursively under the specified key:

`reg delete {{key_name}} /va`

- Forcefully delete all values recursively under a key without a prompt:

`reg delete {{key_name}} /f /va`

