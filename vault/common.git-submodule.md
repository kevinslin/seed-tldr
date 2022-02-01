---
id: common.git-submodule
title: Git Submodule
desc: ''
updated: 1642441815027
created: 1642441815027
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git submodule

> Inspects, updates and manages submodules.
> More information: <https://git-scm.com/docs/git-submodule>.

- Install a repository's specified submodules:

`git submodule update --init --recursive`

- Add a Git repository as a submodule:

`git submodule add {{repository_url}}`

- Add a Git repository as a submodule at the specified directory:

`git submodule add {{repository_url}} {{path/to/directory}}`

- Update every submodule to its latest commit:

`git submodule foreach git pull`

