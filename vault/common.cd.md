---
id: common.cd
title: CD
desc: ''
updated: 1647169313142
created: 1647169313142
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cd

> Change the current working directory.
> More information: <https://manned.org/cd>.

- Go to the specified directory:

`cd {{path/to/directory}}`

- Go up to the parent of the current directory:

`cd ..`

- Go to the home directory of the current user:

`cd`

- Go to the home directory of the specified user:

`cd ~{{username}}`

- Go to the previously chosen directory:

`cd -`

