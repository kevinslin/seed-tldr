---
id: linux.tcptraceroute
title: Tcptraceroute
desc: ''
updated: 1642441815114
created: 1642441815114
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tcptraceroute

> A traceroute implementation using TCP packets.
> More information: <https://github.com/mct/tcptraceroute>.

- Trace the route to a host:

`tcptraceroute {{host}}`

- Specify the destination port and packet length in bytes:

`tcptraceroute {{host}} {{destination_port}} {{packet_length}}`

- Specify the local source port and source address:

`tcptraceroute {{host}} -p {{source_port}} -s {{source_address}}`

- Set the first and maximum TTL:

`tcptraceroute {{host}} -f {{first_ttl}} -m {{max_ttl}}`

- Specify the wait time and number of queries per hop:

`tcptraceroute {{host}} -w {{wait_time}} -q {{number_of_queries}}`

- Specify the interface:

`tcptraceroute {{host}} -i {{interface}}`

