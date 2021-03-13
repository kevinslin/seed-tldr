---
id: osx.netstat
title: Netstat
desc: ''
updated: 1615663978760
created: 1615663978760
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# netstat

> Displays network-related information such as open connections, open socket ports, etc.
> More information: <https://www.unix.com/man-page/osx/1/netstat>.

- List all ports:

`netstat -a`

- List all listening ports:

`netstat -l`

- List listening TCP ports:

`netstat -t`

- Display PID and program names for a specific protocol:

`netstat -p {{protocol}}`

- Print the routing table:

`netstat -nr`

