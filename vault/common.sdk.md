---
id: common.sdk
title: Sdk
desc: ''
updated: 1642441815067
created: 1642441815067
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sdk

> Tool for managing parallel versions of multiple Software Development Kits.
> Supports Java, Groovy, Scala, Kotlin, Gradle, Maven, Vert.x and many others.
> More information: <https://sdkman.io/usage>.

- Install a specific version of Gradle:

`sdk install {{gradle}} {{gradle_version}}`

- Switch to a specific version of Gradle:

`sdk use {{gradle}} {{gradle_version}}`

- Check current Gradle version:

`sdk current {{gradle}}`

- List all Software Development Kits available to install:

`sdk list`

- List all available versions for a specific Software Development Kit:

`sdk list {{sdk_name}}`

- List all installed Software Development Kits:

`sdk current`

- Update Gradle to the latest version:

`sdk upgrade {{gradle}}`

- Uninstall a particular version of Gradle:

`sdk rm {{gradle}} {{gradle_version}}`

