---
id: common.sdk
title: Sdk
desc: ''
updated: 1615663978733
created: 1615663978733
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

- Update Gradle to the latest version:

`sdk upgrade {{gradle}}`

- Uninstall a particular version of Gradle:

`sdk rm {{gradle}} {{gradle_version}}`

