---
id: windows.reg-copy
title: Reg Copy
desc: ''
updated: 1642441815129
created: 1642441815129
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# reg copy

> Copy keys and their values in the registry.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-copy>.

- Copy a registry key to a new registry location:

`reg copy {{old_key_name}} {{new_key_name}}`

- Copy a registry key recursively to a new registry location:

`reg copy {{old_key_name}} {{new_key_name}} /s`

- Forcefully copy a registry key without a prompt:

`reg copy {{old_key_name}} {{new_key_name}} /f`

