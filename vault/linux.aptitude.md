---
id: linux.aptitude
title: Aptitude
desc: ''
updated: 1642441815087
created: 1642441815087
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aptitude

> Debian and Ubuntu package management utility.
> More information: <https://manpages.debian.org/latest/aptitude/aptitude.8.html>.

- Synchronize list of packages and versions available. This should be run first, before running subsequent aptitude commands:

`aptitude update`

- Install a new package and its dependencies:

`aptitude install {{package}}`

- Search for a package:

`aptitude search {{package}}`

- Search for an installed package (`?installed` is an aptitude search term):

`aptitude search '?installed({{package}})'`

- Remove a package and all packages depending on it:

`aptitude remove {{package}}`

- Upgrade installed packages to the newest available versions:

`aptitude upgrade`

- Upgrade installed packages (like `aptitude upgrade`) including removing obsolete packages and installing additional packages to meet new package dependencies:

`aptitude full-upgrade`

- Put an installed package on hold to prevent it from being automatically upgraded:

`aptitude hold '?installed({{package}})'`

