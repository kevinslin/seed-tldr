---
id: windows.choco-new
title: Choco New
desc: ''
updated: 1615655543117
created: 1615655543117
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# choco new

> Generate new package specification files with Chocolatey.
> More information: <https://chocolatey.org/docs/commands-new>.

- Create a new package skeleton:

`choco new {{package_name}}`

- Create a new package with a specific version:

`choco new {{package_name}} --version {{version}}`

- Create a new package with a specific maintainer name:

`choco new {{package_name}} --maintainer {{maintainer_name}}`

- Create a new package in a custom output directory:

`choco new {{package_name}} --output-directory {{path/to/directory}}`

- Create a new package with specific 32-bit and 64-bit installer urls:

`choco new {{package_name}} url="{{url}}" url64="{{url}}"`

