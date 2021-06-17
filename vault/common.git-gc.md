---
id: common.git-gc
title: Git Gc
desc: ''
updated: 1623965016127
created: 1623965016127
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git gc

> Optimise the local repository by cleaning unnecessary files.
> More information: <https://git-scm.com/docs/git-gc>.

- Optimise the repository:

`git gc`

- Aggressively optimise, takes more time:

`git gc --aggressive`

- Do not prune loose objects (prunes by default):

`git gc --no-prune`

- Suppress all output:

`git gc --quiet`

- View full usage:

`git gc --help`

