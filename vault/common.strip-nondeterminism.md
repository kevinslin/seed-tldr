---
id: common.strip-nondeterminism
title: Strip Nondeterminism
desc: ''
updated: 1623965016151
created: 1623965016151
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# strip-nondeterminism

> A tool to remove non-deterministic information (e.g. timestamps) from files.
> More information: <https://salsa.debian.org/reproducible-builds/strip-nondeterminism>.

- Strip nondeterministic information from a file:

`strip-nondeterminism {{path/to/file}}`

- Strip nondeterministic information from a file manually specifying the filetype:

`strip-nondeterminism --type {{filetype}} {{path/to/file}}`

- Strip nondeterministic information from a file; instead of removing timestamps set them to the specified UNIX timestamp:

`strip-nondeterminism --timestamp {{unix_timestamp}} {{path/to/file}}`

