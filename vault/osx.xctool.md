---
id: osx.xctool
title: Xctool
desc: ''
updated: 1615663978761
created: 1615663978761
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xctool

> Tool for building Xcode projects.
> More information: <https://github.com/facebook/xctool>.

- Build a single project without any workspace:

`xctool -project {{YourProject.xcodeproj}} -scheme {{YourScheme}} build`

- Build a project that is part of a workspace:

`xctool -workspace {{YourWorkspace.xcworkspace}} -scheme {{YourScheme}} build`

- Clean, build and execute all the tests:

`xctool -workspace {{YourWorkspace.xcworkspace}} -scheme {{YourScheme}} clean build test`
