---
id: common.fdupes
title: Fdupes
desc: ''
updated: 1615663978709
created: 1615663978709
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fdupes

> Finds duplicate files in a given set of directories.
> More information: <https://github.com/adrianlopezroche/fdupes>.

- Search a single directory:

`fdupes {{directory}}`

- Search multiple directories:

`fdupes {{directory1}} {{directory2}}`

- Search a directory recursively:

`fdupes -r {{directory}}`

- Search multiple directories, one recursively:

`fdupes {{directory1}} -R {{directory2}}`

- Search recursively for duplicates and display interactive prompt to pick which ones to keep, deleting the others:

`fdupes -rd {{directory}}`

- Search recursively and delete duplicates without prompting:

`fdupes -rdN {{directory}}`

