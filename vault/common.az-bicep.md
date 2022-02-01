---
id: common.az-bicep
title: Az Bicep
desc: ''
updated: 1642441814997
created: 1642441814997
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# az bicep

> Bicep CLI command group.
> Part of `azure-cli`.
> More information: <https://docs.microsoft.com/cli/azure/bicep>.

- Install Bicep CLI:

`az bicep install`

- Build a Bicep file:

`az bicep build --file {{path/to/file.bicep}}`

- Attempt to decompile an ARM template file to a Bicep file:

`az bicep decompile --file {{path/to/template_file.json}}`

- Upgrade Bicep CLI to the latest version:

`az bicep upgrade`

- Display the installed version of Bicep CLI:

`az bicep version`

- List all available versions of Bicep CLI:

`az bicep list-versions`

- Uninstall Bicep CLI:

`az bicep uninstall`

