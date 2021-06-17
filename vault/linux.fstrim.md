---
id: linux.fstrim
title: Fstrim
desc: ''
updated: 1623965016162
created: 1623965016162
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fstrim

> Discard unused blocks on a mounted filesystem.
> Only supported by flash memory devices such as SSDs and microSD cards.

- Trim unused blocks on all mounted partitions that support it:

`sudo fstrim --all`

- Trim unused blocks on a specified partition:

`sudo fstrim {{/}}`

- Display statistics after trimming:

`sudo fstrim --verbose {{/}}`

