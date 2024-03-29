---
id: linux.dnf
title: Dnf
desc: ''
updated: 1642441815092
created: 1642441815092
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dnf

> Package management utility for RHEL, Fedora, and CentOS (replaces yum).
> More information: <https://dnf.readthedocs.io>.

- Upgrade installed packages to the newest available versions:

`sudo dnf upgrade`

- Search packages via keywords:

`dnf search {{keywords}}`

- Display details about a package:

`dnf info {{package}}`

- Install a new package:

`sudo dnf install {{package}}`

- Install a new package and assume yes to all questions:

`sudo dnf -y install {{package}}`

- Remove a package:

`sudo dnf remove {{package}}`

- List installed packages:

`dnf list --installed`

- Find which packages provide a given file:

`dnf provides {{file}}`

