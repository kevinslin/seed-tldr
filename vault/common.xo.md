---
id: common.xo
title: Xo
desc: ''
updated: 1642441815085
created: 1642441815085
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xo

> A pluggable, zero-configuration linting utility for JavaScript.
> More information: <https://github.com/xojs/xo>.

- Lint files in the "src" directory:

`xo`

- Lint a given set of files:

`xo {{file1}}.js {{file2}}.js`

- Automatically fix any lint issues found:

`xo --fix`

- Lint using spaces as indentation instead of tabs:

`xo --space`

- Lint using the "prettier" code style:

`xo --prettier`

