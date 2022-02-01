---
id: common.git-show-ref
title: Git Show Ref
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
# git show-ref

> Git command for listing references.
> More information: <https://git-scm.com/docs/git-show-ref>.

- Show all refs in the repository:

`git show-ref`

- Show only heads references:

`git show-ref --heads`

- Show only tags references:

`git show-ref --tags`

- Verify that a given reference exists:

`git show-ref --verify {{path/to/ref}}`

