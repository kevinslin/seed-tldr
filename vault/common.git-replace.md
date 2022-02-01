---
id: common.git-replace
title: Git Replace
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
# git replace

> Create, list, and delete refs to replace objects.
> More information: <https://git-scm.com/docs/git-replace>.

- Replace any commit with a different one, leaving other commits unchanged:

`git replace {{object}} {{replacement}}`

- Delete existing replace refs for the given objects:

`git replace --delete {{object}}`

- Edit an object’s content interactively:

`git replace --edit {{object}}`

