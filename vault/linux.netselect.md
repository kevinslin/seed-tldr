---
id: linux.netselect
title: Netselect
desc: ''
updated: 1615663978750
created: 1615663978750
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# netselect

> Speed test for choosing a fast network server.
> More information: <https://github.com/apenwarr/netselect>.

- Choose the server with the lowest latency:

`sudo netselect {{host_1}} {{host_2}}`

- Display nameserver resolution and statistics:

`sudo netselect -vv {{host_1}} {{host_2}}`

- Define maximum TTL (time to live):

`sudo netselect -m {{10}} {{host_1}} {{host_2}}`

- Print fastest N servers among the hosts:

`sudo netselect -s {{N}} {{host_1}} {{host_2}} {{host_3}}`

- List available options:

`netselect`

