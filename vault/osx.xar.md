---
id: osx.xar
title: Xar
desc: ''
updated: 1615655543116
created: 1615655543116
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# xar

> Manage .xar archives.
> More information: <https://linux.die.net/man/1/xar>.

- Create a xar archive of all files in a given directory:

`xar -cf {{archive.xar}} {{path/to/directory}}`

- Lis[t] the contents of a given xar archive:

`xar -tf {{archive.xar}}`

- Extract the contents of a given xar archive to the current directory:

`xar -xf {{archive.xar}}`

