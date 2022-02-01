---
id: common.kotlinc
title: Kotlinc
desc: ''
updated: 1642441815039
created: 1642441815039
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kotlinc

> Kotlin compiler.
> More information: <https://kotlinlang.org/docs/command-line.html>.

- Start a REPL (interactive shell):

`kotlinc`

- Compile a Kotlin file:

`kotlinc {{path/to/file.kt}}`

- Compile several Kotlin files:

`kotlinc {{path/to/file1.kt path/to/file2.kt ...}}`

- Execute a specific Kotlin Script file:

`kotlinc -script {{path/to/file.kts}}`

- Compile a Kotlin file into a self contained jar file with the Kotlin runtime library included:

`kotlinc {{path/to/file.kt}} -include-runtime -d {{path/to/file.jar}}`

