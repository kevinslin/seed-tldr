---
id: linux.lvextend
title: Lvextend
desc: ''
updated: 1642441815102
created: 1642441815102
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lvextend

> Increase the size of a logical volume.
> See also: `lvm`.
> More information: <https://man7.org/linux/man-pages/man8/lvextend.8.html>.

- Increase a volume's size to 120 GB:

`lvextend --size {{120G}} {{logical_volume}}`

- Increase a volume's size by 40 GB as well as the underlying filesystem:

`lvextend --size +{{40G}} -r {{logical_volume}}`

- Increase a volume's size to 100% of the free physical volume space:

`lvextend --size {{100}}%FREE {{logical_volume}}`

