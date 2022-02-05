---
id: common.lerna
title: Lerna
desc: ''
updated: 1644041260753
created: 1644041260753
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lerna

> A tool for managing JavaScript projects with multiple packages.
> More information: <https://lerna.js.org>.

- Initialize project files (`lerna.json`, `package.json`, `.git`, etc.):

`lerna init`

- Install all external dependencies of each package and symlink together local dependencies:

`lerna bootstrap`

- Run a specific script for every package that contains it in its `package.json`:

`lerna run {{script}}`

- Execute an arbitrary shell command in every package:

`lerna exec -- {{ls}}`

- Publish all packages that have changed since the last release:

`lerna publish`

