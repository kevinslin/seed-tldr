---
id: common.gnucash-cli
title: Gnucash CLI
desc: ''
updated: 1642441815029
created: 1642441815029
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gnucash-cli

> A command-line version of GnuCash.
> More information: <https://gnucash.org>.

- Get quotes for currencies and stocks specified in a file and print them:

`gnucash-cli --quotes get {{path/to/file.gnucash}}`

- Generate a financial report of a specific type, specified by `--name`:

`gnucash-cli --report run --name "{{Balance Sheet}}" {{path/to/file.gnucash}}`

