---
id: common.hg-update
title: Hg Update
desc: ''
updated: 1642441815033
created: 1642441815033
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hg update

> Update the working directory to a specified changeset.
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#update>.

- Update to the tip of the current branch:

`hg update`

- Update to the specified revision:

`hg update --rev {{revision}}`

- Update and discard uncommitted changes:

`hg update --clean`

- Update to the last commit matching a specified date:

`hg update --date {{dd-mm-yyyy}}`

