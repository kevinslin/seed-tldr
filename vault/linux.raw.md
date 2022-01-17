---
id: linux.raw
title: Raw
desc: ''
updated: 1642441815110
created: 1642441815110
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# raw

> Bind a Unix raw character device.
> More information: <https://manned.org/raw.8>.

- Bind a raw character device to a block device:

`raw /dev/raw/raw{{1}} {{/dev/block_device}}`

- Query an existing binding instead of setting a new one:

`raw /dev/raw/raw{{1}}`

- Query all bound raw devices:

`raw -qa`

