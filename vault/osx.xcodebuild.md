---
id: osx.xcodebuild
title: Xcodebuild
desc: ''
updated: 1642441815124
created: 1642441815124
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xcodebuild

> Build Xcode projects.

- Build workspace:

`xcodebuild -workspace {{workspace_name.workspace}} -scheme {{scheme_name}} -configuration {{configuration_name}} clean build SYMROOT={{SYMROOT_path}}`

- Build project:

`xcodebuild -target {{target_name}} -configuration {{configuration_name}} clean build SYMROOT={{SYMROOT_path}}`

- Show SDKs:

`xcodebuild -showsdks`

