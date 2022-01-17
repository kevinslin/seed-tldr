---
id: linux.dpkg
title: Dpkg
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
# dpkg

> Debian package manager.
> Some subcommands such as `dpkg deb` have their own usage documentation.
> More information: <https://manpages.debian.org/latest/dpkg/dpkg.html>.

- Install a package:

`dpkg -i {{path/to/file.deb}}`

- Remove a package:

`dpkg -r {{package_name}}`

- List installed packages:

`dpkg -l {{pattern}}`

- List a package's contents:

`dpkg -L {{package_name}}`

- List contents of a local package file:

`dpkg -c {{path/to/file.deb}}`

- Find out which package owns a file:

`dpkg -S {{filename}}`

