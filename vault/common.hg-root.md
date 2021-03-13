---
id: common.hg-root
title: Hg Root
desc: ''
updated: 1615663978718
created: 1615663978718
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hg root

> Display the root location of a Hg repository.
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#root>.

- Display the root location of the current repository:

`hg root`

- Display the root location of the specified repository:

`hg root --cwd {{path/to/directory}}`
