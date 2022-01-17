---
id: common.git-whatchanged
title: Git Whatchanged
desc: ''
updated: 1642441815028
created: 1642441815028
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git whatchanged

> Show what has changed with recent commits or files.
> See also `git log`.
> More information: <https://git-scm.com/docs/git-whatchanged>.

- Display logs and changes for recent commits:

`git whatchanged`

- Display logs and changes for recent commits within the specified time frame:

`git whatchanged --since="{{2 hours ago}}"`

- Display logs and changes for recent commits for specific files or directories:

`git whatchanged {{path/to/file_or_directory}}`

