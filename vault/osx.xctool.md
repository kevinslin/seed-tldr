---
id: osx.xctool
title: Xctool
desc: ''
updated: 1615655543116
created: 1615655543116
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

