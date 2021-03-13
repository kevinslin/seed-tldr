---
id: common.qcp
title: Qcp
desc: ''
updated: 1615663978731
created: 1615663978731
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qcp

> Copy files using the default text editor to define the filenames.
> More information: <https://www.nongnu.org/renameutils/>.

- Copy a single file (open an editor with the source filename on the left and the target filename on the right):

`qcp {{source_file}}`

- Copy multiple JPG files:

`qcp {{*.jpg}}`

- Copy files, but swap the positions of the source and the target filenames in the editor:

`qcp --option swap {{*.jpg}}`

