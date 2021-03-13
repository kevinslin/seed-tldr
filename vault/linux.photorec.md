---
id: linux.photorec
title: Photorec
desc: ''
updated: 1615655543107
created: 1615655543107
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# photorec

> Deleted file recovery tool.
> It is recommended to write recovered files to a disk separate to the one being recovered from.
> More information: <https://www.cgsecurity.org/wiki/PhotoRec>.

- Run PhotoRec on a specific device:

`sudo photorec {{/dev/sdb}}`

- Run PhotoRec on a disk image (`image.dd`):

`sudo photorec {{path/to/image.dd}}`

