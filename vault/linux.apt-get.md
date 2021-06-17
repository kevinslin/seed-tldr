---
id: linux.apt-get
title: Apt Get
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
# apt-get

> Debian and Ubuntu package management utility.
> Search for packages using `apt-cache`.
> More information: <https://manpages.debian.org/latest/apt/apt-get.8.html>.

- Update the list of available packages and versions (it's recommended to run this before other `apt-get` commands):

`apt-get update`

- Install a package, or update it to the latest available version:

`apt-get install {{package}}`

- Remove a package:

`apt-get remove {{package}}`

- Remove a package and its configuration files:

`apt-get purge {{package}}`

- Upgrade all installed packages to their newest available versions:

`apt-get upgrade`

- Clean the local repository - removing package files (`.deb`) from interrupted downloads that can no longer be downloaded:

`apt-get autoclean`

- Remove all packages that are no longer needed:

`apt-get autoremove`

- Upgrade installed packages (like `upgrade`), but remove obsolete packages and install additional packages to meet new dependencies:

`apt-get dist-upgrade`

