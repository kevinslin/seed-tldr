---
id: common.zipinfo
title: Zipinfo
desc: ''
updated: 1642441815086
created: 1642441815086
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zipinfo

> List detailed information about the contents of a `.zip` file.
> More information: <https://manned.org/zipinfo>.

- List all files in a `.zip` file in long format (permissions, ownership, size, and modification date):

`zipinfo {{path/to/archive.zip}}`

- List all files in a `.zip` file:

`zipinfo -1 {{path/to/archive.zip}}`

