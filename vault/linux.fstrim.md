---
id: linux.fstrim
title: Fstrim
desc: ''
updated: 1642441815095
created: 1642441815095
stub: false
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
> More information: <https://manned.org/fstrim>.

- Trim unused blocks on all mounted partitions that support it:

`sudo fstrim --all`

- Trim unused blocks on a specified partition:

`sudo fstrim {{/}}`

- Display statistics after trimming:

`sudo fstrim --verbose {{/}}`

