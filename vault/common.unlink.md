---
id: common.unlink
title: Unlink
desc: ''
updated: 1615663978737
created: 1615663978737
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unlink

> Remove a link to a file from the filesystem.
> The file contents is lost if the link is the last one to the file.

- Remove the specified file if it is the last link:

`unlink {{path/to/file}}`

