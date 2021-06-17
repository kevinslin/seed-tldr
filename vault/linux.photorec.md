---
id: linux.photorec
title: Photorec
desc: ''
updated: 1623965016166
created: 1623965016166
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# photorec

> Deleted file recovery tool.
> It is recommended to write recovered files to a disk separate to the one being recovered from.
> More information: <https://www.cgsecurity.org/wiki/PhotoRec>.

- Run PhotoRec on a specific device:

`sudo photorec {{/dev/sdb}}`

- Run PhotoRec on a disk image (`image.dd`):

`sudo photorec {{path/to/image.dd}}`

