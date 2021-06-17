---
id: linux.tracepath
title: Tracepath
desc: ''
updated: 1623965306230
created: 1623965306230
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tracepath

> Trace the path to a network host discovering MTU along this path.
> More information: <https://manned.org/tracepath>.

- A preferred way to trace the path to a host:

`tracepath -p {{33434}} {{host}}`

- Specify the initial destination port, useful with non-standard firewall settings:

`tracepath -p {{destination_port}} {{host}} `

- Print both hostnames and numerical IP addresses:

`tracepath -b {{host}}`

- Specify a maximum TTL (number of hops):

`tracepath -m {{max_hops}} {{host}}`

- Specify the initial packet length (defaults to 65535 for IPv4 and 128000 for IPv6):

`tracepath -l {{packet_length}} {{host}}`

- Use only IPv6 addresses:

`tracepath -6 {{host}}`

