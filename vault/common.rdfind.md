---
id: common.rdfind
title: Rdfind
desc: ''
updated: 1615663978732
created: 1615663978732
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rdfind

> Find files with duplicate content and get rid of them.
> More information: <https://rdfind.pauldreik.se>.

- Identify all duplicates in a given directory and output a summary:

`rdfind -dryrun true {{path/to/directory}}`

- Replace all duplicates with hardlinks:

`rdfind -makehardlinks true {{path/to/directory}}`

- Replace all duplicates with symlinks/soft links:

`rdfind -makesymlinks true {{path/to/directory}}`

- Delete all duplicates and do not ignore empty files:

`rdfind -deleteduplicates true -ignoreempty false {{path/to/directory}}`

