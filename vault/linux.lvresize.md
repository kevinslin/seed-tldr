---
id: linux.lvresize
title: Lvresize
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
# lvresize

> Change the size of a logical volume.
> See also: `lvm`.
> More information: <https://man7.org/linux/man-pages/man8/lvresize.8.html>.

- Change the size of a logical volume to 120 GB:

`lvresize --size {{120G}} {{volume_group}}/{{logical_volume}}`

- Extend the size of a logical volume as well as the underlying filesystem by 120 GB:

`lvresize --size +{{120G}} --resizefs {{volume_group}}/{{logical_volume}}`

- Extend the size of a logical volume to 100% of the free physical volume space:

`lvresize --size {{100}}%FREE {{volume_group}}/{{logical_volume}}`

- Reduce the size of a logical volume as well as the underlying filesystem by 120 GB:

`lvresize --size -{{120G}} --resizefs {{volume_group}}/{{logical_volume}}`

