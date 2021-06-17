---
id: windows.choco-install
title: Choco Install
desc: ''
updated: 1623965016176
created: 1623965016176
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# choco install

> Install one or more packages with Chocolatey.
> More information: <https://chocolatey.org/docs/commands-install>.

- Install one or more space-separated packages:

`choco install {{package(s)}}`

- Install packages from a custom configuration file:

`choco install {{path/to/packages.config}}`

- Install a specific nuspec or nupkg file:

`choco install {{path/to/file}}`

- Install a specific version of a package:

`choco install {{package}} --version {{version}}`

- Allow installing multiple versions of a package:

`choco install {{package}} --allow-multiple`

- Confirm all prompts automatically:

`choco install {{package}} --yes`

- Specify a custom source to receive packages from:

`choco install {{package}} --source {{source_url|alias}}`

- Provide a username and password for authentication:

`choco install {{package}} --user {{username}} --password {{password}}`

