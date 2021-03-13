---
id: common.mr
title: Mr
desc: ''
updated: 1615663978725
created: 1615663978725
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mr

> Myrepos manages all your version control repositories at once.
> More information: <https://myrepos.branchable.com>.

- Register a repository:

`mr register`

- Update repositories in 5 concurrent jobs:

`mr -j{{5}} update`

- Print the status of all repositories:

`mr status`

- Checkout all repositories to the latest version:

`mr checkout`

