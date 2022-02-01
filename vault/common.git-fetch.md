---
id: common.git-fetch
title: Git Fetch
desc: ''
updated: 1642441815023
created: 1642441815023
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git fetch

> Download objects and refs from a remote repository.
> More information: <https://git-scm.com/docs/git-fetch>.

- Fetch the latest changes from the default remote upstream repository (if set):

`git fetch`

- Fetch new branches from a specific remote upstream repository:

`git fetch {{remote_name}}`

- Fetch the latest changes from all remote upstream repositories:

`git fetch --all`

- Also fetch tags from the remote upstream repository:

`git fetch --tags`

- Delete local references to remote branches that have been deleted upstream:

`git fetch --prune`

