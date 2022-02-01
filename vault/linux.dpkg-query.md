---
id: linux.dpkg-query
title: Dpkg Query
desc: ''
updated: 1642441815093
created: 1642441815093
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dpkg-query

> A tool that shows information about installed packages.
> More information: <https://manpages.debian.org/latest/dpkg/dpkg-query.1.html>.

- List all installed packages:

`dpkg-query -l`

- List installed packages matching a pattern:

`dpkg-query -l '{{pattern}}'`

- List all files installed by a package:

`dpkg-query -L {{package_name}}`

- Show information about a package:

`dpkg-query -s {{package_name}}`

