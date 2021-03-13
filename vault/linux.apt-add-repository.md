---
id: linux.apt-add-repository
title: Apt Add Repository
desc: ''
updated: 1615663978741
created: 1615663978741
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apt-add-repository

> Manages apt repository definitions.

- Add a new apt repository:

`apt-add-repository {{repository_spec}}`

- Remove an apt repository:

`apt-add-repository --remove {{repository_spec}}`

- Update the package cache after adding a repository:

`apt-add-repository --update {{repository_spec}}`

- Enable source packages:

`apt-add-repository --enable-source {{repository_spec}}`

