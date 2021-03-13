---
id: linux.iftop
title: Iftop
desc: ''
updated: 1615663978747
created: 1615663978747
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# iftop

> Show bandwidth usage on an interface by host.
> More information: <https://linux.die.net/man/8/iftop>.

- Show the bandwidth usage:

`sudo iftop`

- Show the bandwidth usage of a given interface:

`sudo iftop -i {{interface}}`

- Show the bandwidth usage with port information:

`sudo iftop -P`

- Do not show bar graphs of traffic:

`sudo iftop -b`

- Do not look up hostnames:

`sudo iftop -n`

- Get help about interactive commands:

`?`

