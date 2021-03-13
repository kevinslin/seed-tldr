---
id: linux.isosize
title: Isosize
desc: ''
updated: 1615663978748
created: 1615663978748
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# isosize

> Display the size of an ISO file.
> More information: <https://linux.die.net/man/8/isosize>.

- Display the size of an ISO file:

`isosize {{path/to/file.iso}}`

- Display the block count and block size of an ISO file:

`isosize --sectors {{path/to/file.iso}}`

- Display the size of an ISO file divided by a given number (only usable when --sectors is not given):

`isosize --divisor={{number}} {{path/to/file.iso}}`
