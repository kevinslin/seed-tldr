---
id: windows.iscc
title: Iscc
desc: ''
updated: 1623965016177
created: 1623965016177
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# iscc

> Compiler for Inno Setup installers.
> It compiles an Inno Setup scripts into an Windows installer executable.
> More information: <https://jrsoftware.org/isinfo.php>.

- Compile an Inno Setup script:

`iscc {{path/to/file.iss}}`

- Quietly compile an Inno Setup installer:

`iscc /Q {{path/to/file.iss}}`

- Compile a signed Inno Setup installer:

`iscc /S={{name}}={{command}} {{path/to/file.iss}}`

