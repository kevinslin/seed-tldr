---
id: common.shred
title: Shred
desc: ''
updated: 1615663978734
created: 1615663978734
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shred

> Overwrite files to securely delete data.

- Overwrite a file:

`shred {{file}}`

- Overwrite a file, leaving zeroes instead of random data:

`shred --zero {{file}}`

- Overwrite a file 25 times:

`shred -n25 {{file}}`

- Overwrite a file and remove it:

`shred --remove {{file}}`

