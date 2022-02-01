---
id: common.trawl
title: Trawl
desc: ''
updated: 1642441815077
created: 1642441815077
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# trawl

> Prints out network interface information to the console, much like ifconfig/ipconfig/ip/ifdata.
> More information: <https://github.com/robphoenix/trawl>.

- Show column names:

`trawl -n`

- Filter interface names using a case-insensitive regular expression:

`trawl -f wi`

- Get a list of available interfaces:

`trawl -i`

- Include the loopback interface:

`trawl -l`

