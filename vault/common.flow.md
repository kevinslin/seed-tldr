---
id: common.flow
title: Flow
desc: ''
updated: 1642441815018
created: 1642441815018
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# flow

> A static type checker for JavaScript.
> More information: <https://flow.org>.

- Run a flow check:

`flow`

- Check which files are being checked by flow:

`flow ls`

- Run a type coverage check on all files in a directory:

`flow batch-coverage --show-all --strip-root {{path/to/directory}}`

- Display line-by-line type coverage stats:

`flow coverage --color {{path/to/file.jsx}}`

