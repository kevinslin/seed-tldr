---
id: linux.isosize
title: Isosize
desc: ''
updated: 1623965016163
created: 1623965016163
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# isosize

> Display the size of an ISO file.
> More information: <https://manned.org/isosize>.

- Display the size of an ISO file:

`isosize {{path/to/file.iso}}`

- Display the block count and block size of an ISO file:

`isosize --sectors {{path/to/file.iso}}`

- Display the size of an ISO file divided by a given number (only usable when --sectors is not given):

`isosize --divisor={{number}} {{path/to/file.iso}}`

