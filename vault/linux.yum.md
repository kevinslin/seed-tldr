---
id: linux.yum
title: Yum
desc: ''
updated: 1643128140548
created: 1643128140548
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# yum

> Package management utility for RHEL, Fedora, and CentOS (for older versions).
> More information: <https://manned.org/yum>.

- Install a new package:

`yum install {{package}}`

- Install a new package and assume yes to all questions (also works with update, great for automated updates):

`yum -y install {{package}}`

- Find the package that provides a particular command:

`yum provides {{command}}`

- Remove a package:

`yum remove {{package}}`

- Display available updates for installed packages:

`yum check-update`

- Upgrade installed packages to the newest available versions:

`yum upgrade`

