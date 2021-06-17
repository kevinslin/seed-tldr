---
id: common.git-am
title: Git Am
desc: ''
updated: 1623965016126
created: 1623965016126
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git am

> Apply patch files. Useful when receiving commits via email.
> See also `git format-patch`, which can generate patch files.
> More information: <https://git-scm.com/docs/git-am>.

- Apply a patch file:

`git am {{path/to/file.patch}}`

- Abort the process of applying a patch file:

`git am --abort`

- Apply as much of a patch file as possible, saving failed hunks to reject files:

`git am --reject {{path/to/file.patch}}`

