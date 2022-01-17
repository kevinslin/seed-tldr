---
id: windows.choco-source
title: Choco Source
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
# choco source

> Manage sources for packages with Chocolatey.
> More information: <https://chocolatey.org/docs/commands-source>.

- List currently available sources:

`choco source list`

- Add a new package source:

`choco source add --name {{name}} --source {{url}}`

- Add a new package source with credentials:

`choco source add --name {{name}} --source {{url}} --user {{username}} --password {{password}}`

- Add a new package source with a client certificate:

`choco source add --name {{name}} --source {{url}} --cert {{path/to/certificate}}`

- Enable a package source:

`choco source enable --name {{name}}`

- Disable a package source:

`choco source disable --name {{name}}`

- Remove a package source:

`choco source remove --name {{name}}`

