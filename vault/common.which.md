---
id: common.which
title: Which
desc: ''
updated: 1623965306216
created: 1623965306216
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# which

> Locate a program in the user's path.

- Search the PATH environment variable and display the location of any matching executables:

`which {{executable}}`

- If there are multiple executables which match, display all:

`which -a {{executable}}`

