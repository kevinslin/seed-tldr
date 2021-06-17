---
id: common.git-ls-tree
title: Git Ls Tree
desc: ''
updated: 1623965306188
created: 1623965306188
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git ls-tree

> List the contents of a tree object.
> More information: <https://git-scm.com/docs/git-ls-tree>.

- List the contents of the tree on a branch:

`git ls-tree {{branch_name}}`

- List the contents of the tree on a commit, recursing into subtrees:

`git ls-tree -r {{commit_hash}}`

- List only the filenames of the tree on a commit:

`git ls-tree --name-only {{commit_hash}}`

