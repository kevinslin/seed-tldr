---
id: linux.apt-add-repository
title: Apt Add Repository
desc: ''
updated: 1623965306219
created: 1623965306219
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apt-add-repository

> Manages apt repository definitions.
> More information: <https://manpages.debian.org/latest/software-properties-common/apt-add-repository.1.html>.

- Add a new apt repository:

`apt-add-repository {{repository_spec}}`

- Remove an apt repository:

`apt-add-repository --remove {{repository_spec}}`

- Update the package cache after adding a repository:

`apt-add-repository --update {{repository_spec}}`

- Enable source packages:

`apt-add-repository --enable-source {{repository_spec}}`

