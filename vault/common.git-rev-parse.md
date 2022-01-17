---
id: common.git-rev-parse
title: Git Rev Parse
desc: ''
updated: 1642441815026
created: 1642441815026
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git rev-parse

> Display metadata related to specific revisions.
> More information: <https://git-scm.com/docs/git-rev-parse>.

- Get the commit hash of a branch:

`git rev-parse {{branch_name}}`

- Get the current branch name:

`git rev-parse --abbrev-ref {{HEAD}}`

- Get the absolute path to the root directory:

`git rev-parse --show-toplevel`

