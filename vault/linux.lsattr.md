---
id: linux.lsattr
title: Lsattr
desc: ''
updated: 1623965306224
created: 1623965306224
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lsattr

> List file attributes on a Linux filesystem.

- Display the attributes of the files in the current directory:

`lsattr`

- List the attributes of files in a particular path:

`lsattr {{path}}`

- List file attributes recursively in the current and subsequent directories:

`lsattr -R`

- Show attributes of all the files in the current directory, including hidden ones:

`lsattr -a`

- Display attributes of directories in the current directory:

`lsattr -d`

