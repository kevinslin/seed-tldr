---
id: windows.reg-compare
title: Reg Compare
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
# reg compare

> Compare keys and their values in the registry.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/reg-compare>.

- Compare all values under a specific key with a second key:

`reg compare {{first_key_name}} {{second_key_name}}`

- Compare a specific value under two keys:

`reg compare {{first_key_name}} {{second_key_name}} /v {{value}}`

- Compare all sub keys and values for two keys:

`reg compare {{first_key_name}} {{second_key_name}} /s`

- Only output the matches between the specified keys:

`reg compare {{first_key_name}} {{second_key_name}} /os`

- Output the differences and matches between the specified keys:

`reg compare {{first_key_name}} {{second_key_name}} /oa`

