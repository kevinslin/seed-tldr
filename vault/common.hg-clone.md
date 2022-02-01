---
id: common.hg-clone
title: Hg Clone
desc: ''
updated: 1642441815032
created: 1642441815032
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hg clone

> Create a copy of an existing repository in a new directory.
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#clone>.

- Clone a repository to a specified directory:

`hg clone {{remote_repository_source}} {{destination_path}}`

- Clone a repository to the head of a specific branch, ignoring later commits:

`hg clone --branch {{branch}} {{remote_repository_source}}`

- Clone a repository with only the `.hg` directory, without checking out files:

`hg clone --noupdate {{remote_repository_source}}`

- Clone a repository to a specific revision, tag or branch, keeping the entire history:

`hg clone --updaterev {{revision}} {{remote_repository_source}}`

- Clone a repository up to a specific revision without any newer history:

`hg clone --rev {{revision}} {{remote_repository_source}}`

