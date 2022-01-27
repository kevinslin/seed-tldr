---
id: common.mktemp
title: Mktemp
desc: ''
updated: 1643245477405
created: 1643245477405
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

- Create an empty temporary file and print the absolute path to it:

`mktemp`

- Create an empty temporary file with a given suffix and print the absolute path to file:

`mktemp --suffix "{{.ext}}"`

- Create a temporary directory and print the absolute path to it (non-portable long option: --directory):

`mktemp -d`

