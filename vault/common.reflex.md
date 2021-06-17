---
id: common.reflex
title: Reflex
desc: ''
updated: 1623965016147
created: 1623965016147
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# reflex

> Tool to watch a directory and rerun a command when certain files change.
> More information: <https://github.com/cespare/reflex>.

- Rebuild with `make` if any file changes:

`reflex make`

- Compile and run Go application if any `.go` file changes:

`reflex --regex='{{\.go$}}' {{go run .}}`

- Ignore a directory when watching for changes:

`reflex --inverse-regex='{{^dir/}}' {{command}}`

- Run command when reflex starts and restarts on file changes:

`reflex --start-service=true {{command}}`

- Substitute the filename that changed in:

`reflex -- echo {}`

