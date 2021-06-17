---
id: linux.nmon
title: Nmon
desc: ''
updated: 1623965306226
created: 1623965306226
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nmon

> A system administrator, tuner, and benchmark tool.

- Start nmon:

`nmon`

- Save records to file ("-s 300 -c 288" by default):

`nmon -f`

- Save records to file with a total of 240 measurements, by taking 30 seconds between each measurement:

`nmon -f -s {{30}} -c {{240}}`

