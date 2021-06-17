---
id: osx.carthage
title: Carthage
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
# carthage

> A dependency management tool for Cocoa applications.

- Download the latest version of all dependencies mentioned in Cartfile, and build them:

`carthage update`

- Update dependencies, but only build for iOS:

`carthage update --platform ios`

- Update dependencies, but don't build any of them:

`carthage update --no-build`

- Download and rebuild the current version of dependencies (without updating them):

`carthage bootstrap`

- Rebuild a specific dependency:

`carthage build {{dependency}}`

