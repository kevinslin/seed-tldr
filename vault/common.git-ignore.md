---
id: common.git-ignore
title: Git Ignore
desc: ''
updated: 1642441815024
created: 1642441815024
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git ignore

> Show/update `.gitignore` files.
> Part of `git-extras`. See also `git ignore-io`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-ignore>.

- Show the content of all global and local `.gitignore` files:

`git ignore`

- Ignore file(s) privately, updating `.git/info/exclude` file:

`git ignore {{file_pattern}} --private`

- Ignore file(s) locally, updating local `.gitignore` file:

`git ignore {{file_pattern}}`

- Ignore file(s) globally, updating global `.gitignore` file:

`git ignore {{file_pattern}} --global`

