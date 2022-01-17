---
id: common.unlink
title: Unlink
desc: ''
updated: 1642441815079
created: 1642441815079
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unlink

> Remove a link to a file from the filesystem.
> The file contents is lost if the link is the last one to the file.
> More information: <https://www.gnu.org/software/coreutils/unlink>.

- Remove the specified file if it is the last link:

`unlink {{path/to/file}}`

