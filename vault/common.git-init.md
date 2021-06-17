---
id: common.git-init
title: Git Init
desc: ''
updated: 1623965306187
created: 1623965306187
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git init

> Initializes a new local Git repository.
> More information: <https://git-scm.com/docs/git-init>.

- Initialize a new local repository:

`git init`

- Initialize a repository with the specified name for the initial branch:

`git init --initial-branch={{branch_name}}`

- Initialize a repository using SHA256 for object hashes (requires Git version 2.29+):

`git init --object-format={{sha256}}`

- Initialize a barebones repository, suitable for use as a remote over ssh:

`git init --bare`

