---
id: common.git-filter-repo
title: Git Filter Repo
desc: ''
updated: 1642441815024
created: 1642441815024
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git filter-repo

> A versatile tool for rewriting Git history.
> See also: `bfg`.
> More information: <https://github.com/newren/git-filter-repo>.

- Replace a sensitive string in all files:

`git filter-repo --replace-text <(echo '{{find}}==>{{replacement}}')`

- Extract a single folder, keeping history:

`git-filter-repo --path {{path/to/folder}}`

- Remove a single folder, keeping history:

`git-filter-repo --path {{path/to/folder}} --invert-paths`

- Move everything from sub-folder one level up:

`git-filter-repo --path-rename {{path/to/folder/:}}`

