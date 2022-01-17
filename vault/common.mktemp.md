---
id: common.mktemp
title: Mktemp
desc: ''
updated: 1642441815047
created: 1642441815047
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mktemp

> Create a temporary file or directory.
> More information: <https://www.gnu.org/software/autogen/mktemp.html>.

- Create an empty temporary file and return the absolute path to it:

`mktemp`

- Create a temporary directory and return the absolute path to it:

`mktemp -d`

- Create a temporary file with a specified suffix:

`mktemp --suffix "{{.txt}}"`

