---
id: common.hping
title: Hping
desc: ''
updated: 1642441815033
created: 1642441815033
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hping

> Command-line oriented TCP/IP packet assembler and analyzer.
> Inspired by the `ping` command.
> More information: <http://www.hping.org>.

- Ping localhost over TCP:

`hping3 {{localhost}}`

- Ping an IP address over TCP on a specific port:

`hping3 -p {{80}} -S {{192.168.1.1}}`

- Ping an IP address over UDP on port 80:

`hping3 --udp -p {{80}} -S {{192.168.1.1}}`

- Scan a set of TCP ports on a specific IP address:

`hping3 --scan {{80,3000,9000}} -S {{192.168.1.1}}`

- Perform a charge test on port 80:

`hping3 --flood -p {{80}} -S {{192.168.1.1}}`

