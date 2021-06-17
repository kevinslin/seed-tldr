---
id: common.ioping
title: Ioping
desc: ''
updated: 1623965016132
created: 1623965016132
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ioping

> Monitor I/O latency in real time.
> More information: <https://github.com/koct9i/ioping>.

- Show disk I/O latency using the default values and the current directory:

`ioping .`

- Measure latency on /tmp using 10 requests of 1 megabyte each:

`ioping -c 10 -s 1M /tmp`

- Measure disk seek rate on `/dev/sdX`:

`ioping -R {{/dev/sdX}}`

- Measure disk sequential speed on `/dev/sdX`:

`ioping -RL {{/dev/sdX}}`

