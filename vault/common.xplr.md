---
id: common.xplr
title: Xplr
desc: ''
updated: 1642441815085
created: 1642441815085
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xplr

> Terminal-based file system explorer.
> More information: <https://xplr.dev>.

- Open a directory:

`xplr {{path/to/directory}}`

- Focus on a file:

`xplr {{path/to/file}}`

- Focus on a directory:

`xplr --force-focus {{path/to/directory}}`

- Open a directory with specific files or directories selected:

`xplr {{path/to/directory}} {{path/to/selected_file_or_directory1}} {{path/to/selected_file_or_directory2}}`

