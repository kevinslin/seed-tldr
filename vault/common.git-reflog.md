---
id: common.git-reflog
title: Git Reflog
desc: ''
updated: 1642441815025
created: 1642441815025
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git reflog

> Show a log of changes to local references like HEAD, branches or tags.
> More information: <https://git-scm.com/docs/git-reflog>.

- Show the reflog for HEAD:

`git reflog`

- Show the reflog for a given branch:

`git reflog {{branch_name}}`

- Show only the 5 latest entries in the reflog:

`git reflog -n {{5}}`

