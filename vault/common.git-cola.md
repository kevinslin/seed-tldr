---
id: common.git-cola
title: Git Cola
desc: ''
updated: 1642441815022
created: 1642441815022
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git cola

> A powerful Git GUI with a slick and intuitive user interface.
> More information: <https://git-cola.readthedocs.io>.

- Start git cola:

`git cola`

- Start git cola in amend mode:

`git cola --amend`

- Prompt for a Git repository. Defaults to the current directory:

`git cola --prompt`

- Open the Git repository at mentioned path:

`git cola --repo {{path/to/git-repository}}`

- Apply the path filter to the status widget:

`git cola --status-filter {{filter}}`

