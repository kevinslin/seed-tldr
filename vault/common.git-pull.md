---
id: common.git-pull
title: Git Pull
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
# git pull

> Fetch branch from a remote repository and merge it to local repository.
> More information: <https://git-scm.com/docs/git-pull>.

- Download changes from default remote repository and merge it:

`git pull`

- Download changes from default remote repository and use fast-forward:

`git pull --rebase`

- Download changes from given remote repository and branch, then merge them into HEAD:

`git pull {{remote_name}} {{branch}}`

