---
id: common.git-release
title: Git Release
desc: ''
updated: 1623965016128
created: 1623965016128
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git release

> Create a Git tag for a release.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-release>.

- Create and push a release:

`git release {{tag_name}}`

- Create and push a signed release:

`git release {{tag_name}} -s`

- Create and push a release with a message:

`git release {{{tag_name}}} -m "{{message}}"`

