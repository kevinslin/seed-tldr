---
id: common.sdiff
title: Sdiff
desc: ''
updated: 1642441815067
created: 1642441815067
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sdiff

> Compare the differences between and optionally merge 2 files.
> More information: <https://manned.org/sdiff>.

- Compare 2 files:

`sdiff {{path/to/file1}} {{path/to/file2}}`

- Compare 2 files, ignoring all tabs and whitespace:

`sdiff -W {{path/to/file1}} {{path/to/file2}}`

- Compare 2 files, ignoring whitespace at the end of lines:

`sdiff -Z {{path/to/file1}} {{path/to/file2}}`

- Compare 2 files in a case-insensitive manner:

`sdiff -i {{path/to/file1}} {{path/to/file2}}`

- Compare and then merge, writing the output to a new file:

`sdiff -o {{path/to/merged_file}} {{path/to/file1}} {{path/to/file2}}`

