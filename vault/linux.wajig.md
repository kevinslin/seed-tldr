---
id: linux.wajig
title: Wajig
desc: ''
updated: 1642441815117
created: 1642441815117
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wajig

> Simplified all-in-one-place system support tool for Debian-based systems.
> More information: <https://wajig.togaware.com>.

- Update the list of available packages and versions:

`wajig update`

- Install a package, or update it to the latest available version:

`wajig install {{package}}`

- Remove a package and its configuration files:

`wajig purge {{package}}`

- Perform an update and then a dist-upgrade:

`wajig daily-upgrade`

- Display the sizes of installed packages:

`wajig sizes`

- List the version and distribution for all installed packages:

`wajig versions`

- List versions of upgradable packages:

`wajig toupgrade`

- Display packages which have some form of dependency on the given package:

`wajig dependents {{package}}`

