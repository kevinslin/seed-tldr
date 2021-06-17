---
id: common.makensis
title: Makensis
desc: ''
updated: 1623965016135
created: 1623965016135
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# makensis

> Cross-platform compiler for NSIS installers.
> It compiles a NSIS script into a Windows installer executable.
> More information: <https://nsis.sourceforge.io/Docs/Chapter3.html>.

- Compile a NSIS script:

`makensis {{path/to/file.nsi}}`

- Compile a NSIS script in strict mode (treat warnings as errors):

`makensis -WX {{path/to/file.nsi}}`

- Print help for a specific command:

`makensis -CMDHELP {{command}}`

