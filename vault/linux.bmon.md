---
id: linux.bmon
title: Bmon
desc: ''
updated: 1642441815089
created: 1642441815089
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bmon

> Monitor bandwidth and capture network related statistics.
> More information: <https://github.com/tgraf/bmon>.

- Display the list of all the interfaces:

`bmon -a`

- Display data transfer rates in bits per second:

`bmon -b`

- Set policy to define which network interface(s) is/are displayed:

`bmon -p {{interface_1,interface_2,interface_3}}`

- Set interval (in seconds) in which rate per counter is calculated:

`bmon -R {{2.0}}`

