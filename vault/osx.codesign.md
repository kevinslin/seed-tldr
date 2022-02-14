---
id: osx.codesign
title: Codesign
desc: ''
updated: 1644840636307
created: 1644840636307
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# codesign

> Create and manipulate code signatures for macOS.
> More information: <https://www.unix.com/man-page/osx/1/codesign/>.

- Sign an application with a certificate:

`codesign --sign "{{My Company Name}}" {{path/to/App.app}}`

- Verify the certificate of an application:

`codesign --verify {{path/to/App.app}}`

