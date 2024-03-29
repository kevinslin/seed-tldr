---
id: linux.gdebi
title: Gdebi
desc: ''
updated: 1642441815096
created: 1642441815096
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gdebi

> Simple tool to install `.deb` files.
> More information: <https://www.commandlinux.com/man-page/man1/gdebi.1.html>.

- Install local `.deb` packages resolving and installing its dependencies:

`gdebi {{path/to/package.deb}}`

- Display the program version:

`gdebi --version`

- Do not show progress information:

`gdebi {{path/to/package.deb}} --quiet`

- Set an APT configuration option:

`gdebi {{path/to/package.deb}} --option={{APT_OPTS}}`

- Use alternative root dir:

`gdebi {{path/to/package.deb}} --root={{path/to/root_dir}}`

