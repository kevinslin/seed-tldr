---
id: osx.nettop
title: Nettop
desc: ''
updated: 1644840636310
created: 1644840636310
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nettop

> Display updated information about the network.
> More information: <https://www.manpagez.com/man/1/nettop/>.

- Monitor TCP and UDP sockets from all interfaces:

`nettop`

- Monitor TCP sockets from Loopback interfaces:

`nettop -m {{tcp}} -t {{loopback}}`

- Monitor a specific process:

`nettop -p "{{process_id|process_name}}"`

- Display a per-process summary:

`nettop -P`

- Print 10 samples of network information:

`nettop -l {{10}}`

- Monitor changes every 5 seconds:

`nettop -d -s {{5}}`

- While running nettop, list interactive commands:

`h`

- Display help:

`nettop -h`

