---
id: linux.pvcreate
title: Pvcreate
desc: ''
updated: 1623965306228
created: 1623965306228
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pvcreate

> Initialize a disk or partition for use as a physical volume.
> See also: `lvm`.
> More information: <https://man7.org/linux/man-pages/man8/pvcreate.8.html>.

- Initialize the `/dev/sda1` volume for use by LVM:

`pvcreate {{/dev/sda1}}`

- Force the creation without any confirmation prompts:

`pvcreate --force {{/dev/sda1}}`

