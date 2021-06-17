---
id: common.install
title: Install
desc: ''
updated: 1623965306193
created: 1623965306193
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# install

> Copy files and set attributes.
> Copy files (often executable) to a system location like `/usr/local/bin`, give them the appropriate permissions/ownership.
> More information: <https://www.gnu.org/software/coreutils/install>.

- Copy files to destination:

`install {{path/to/source}} {{path/to/destination}}`

- Copy files to destination, setting their ownership:

`install -o {{user}} {{path/to/source}} {{path/to/destination}}`

- Copy files to destination, setting their group ownership:

`install -g {{user}} {{path/to/source}} {{path/to/destination}}`

- Copy files to destination, setting their `mode`:

`install -m {{+x}} {{path/to/source}} {{path/to/destination}}`

- Copy files and apply access/modification times of source to destination:

`install -p {{path/to/source}} {{path/to/destination}}`

