---
id: windows.choco-outdated
title: Choco Outdated
desc: ''
updated: 1642441815126
created: 1642441815126
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# choco outdated

> Check for outdated packages with Chocolatey.
> More information: <https://chocolatey.org/docs/commands-outdated>.

- Display a list of outdated packages in table format:

`choco outdated`

- Ignore pinned packages in the output:

`choco outdated --ignore-pinned`

- Specify a custom source to check packages from:

`choco outdated --source {{source_url|alias}}`

- Provide a username and password for authentication:

`choco outdated --user {{username}} --password {{password}}`

