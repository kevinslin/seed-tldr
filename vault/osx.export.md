---
id: osx.export
title: Export
desc: ''
updated: 1623965016173
created: 1623965016173
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# export

> Command to mark shell variables in the current environment to be exported with any newly forked child processes.

- Set a new environment variable:

`export {{VARIABLE}}={{value}}`

- Remove an environment variable:

`export -n {{VARIABLE}}`

- Append something to the PATH variable:

`export PATH=$PATH:{{path/to/append}}`

