---
id: common.srm
title: Srm
desc: ''
updated: 1615663978735
created: 1615663978735
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# srm

> Securely remove files or directories.
> Overwrites the existing data one or multiple times. Drop in replacement for rm.
> More information: <http://srm.sourceforge.net/srm.html>.

- Remove a file after a single-pass overwriting with random data:

`srm -s {{path/to/file}}`

- Remove a file after seven passes of overwriting with random data:

`srm -m {{path/to/file}}`

- Recursively remove a directory and its contents overwriting each file with a single-pass of random data:

`srm -r -s {{path/to/directory}}`

- Prompt before every removal:

`srm -i {{\*}}`

