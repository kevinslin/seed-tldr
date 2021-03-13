---
id: linux.lvreduce
title: Lvreduce
desc: ''
updated: 1615663978749
created: 1615663978749
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lvreduce

> Reduce the size of a logical volume.
> See also: `lvm`.
> More information: <https://man7.org/linux/man-pages/man8/lvreduce.8.html>.

- Reduce a volume's size to 120GB:

`lvreduce --size {{120G}} {{logical_volume}}`

- Reduce a volume's size by 40GB as well as the underlying filesystem:

`lvreduce --size -{{40G}} -r {{logical_volume}}`

