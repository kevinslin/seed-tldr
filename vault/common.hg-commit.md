---
id: common.hg-commit
title: Hg Commit
desc: ''
updated: 1615663978718
created: 1615663978718
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hg commit

> Commit all staged or specified files to the repository.
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#commit>.

- Commit staged files to the repository:

`hg commit`

- Commit a specific file or directory:

`hg commit {{path/to/file_or_directory}}`

- Commit with a specific message:

`hg commit --message {{message}}`

- Commit all files matching a specified pattern:

`hg commit --include {{pattern}}`

- Commit all files, excluding those that match a specified pattern:

`hg commit --exclude {{pattern}}`

- Commit using the interactive mode:

`hg commit --interactive`

