---
id: osx.codesign
title: Codesign
desc: ''
updated: 1623965306233
created: 1623965306233
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# codesign

> Create and manipulate code signatures for macOS.

- Sign an application with a certificate:

`codesign -s "{{My Company Name}}" {{path/to/App.app}}`

- Verify the certificate of an application:

`codesign -v {{path/to/App.app}}`

