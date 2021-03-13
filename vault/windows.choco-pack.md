---
id: windows.choco-pack
title: Choco Pack
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# choco pack

> Package a NuGet specification into a nupkg file.
> More information: <https://chocolatey.org/docs/commands-pack>.

- Package a NuGet specification to a nupkg file:

`choco pack {{path/to/specification}}`

- Package a NuGet specification specifying the version of the resulting file:

`choco pack {{path/to/specification}} --version {{version}}`

- Package a NuGet specification to a specific directory:

`choco pack {{path/to/specification}} --output-directory {{path/to/output_directory}}`

