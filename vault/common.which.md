---
id: common.which
title: Which
desc: ''
updated: 1642441815083
created: 1642441815083
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# which

> Locate a program in the user's path.
> More information: <https://manned.org/which>.

- Search the PATH environment variable and display the location of any matching executables:

`which {{executable}}`

- If there are multiple executables which match, display all:

`which -a {{executable}}`

