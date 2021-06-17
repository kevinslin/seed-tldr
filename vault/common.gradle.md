---
id: common.gradle
title: Gradle
desc: ''
updated: 1623965016130
created: 1623965016130
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gradle

> Gradle is an open source build automation system.
> More information: <https://gradle.org>.

- Compile a package:

`gradle build`

- Exclude test task:

`gradle build -x {{test}}`

- Run in offline mode to prevent gradle from accessing the network during builds:

`gradle build --offline`

- Clear the build directory:

`gradle clean`

- Compile and Release package:

`gradle assembleRelease`

- List the main tasks:

`gradle tasks`

- List all the tasks:

`gradle tasks --all`

