---
id: windows.choco-new
title: Choco New
desc: ''
updated: 1623965306237
created: 1623965306237
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

- Create a new package with specific 32-bit and 64-bit installer URLs:

`choco new {{package_name}} url="{{url}}" url64="{{url}}"`

