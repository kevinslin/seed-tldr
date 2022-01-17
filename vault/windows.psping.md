---
id: windows.psping
title: Psping
desc: ''
updated: 1642441815128
created: 1642441815128
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# psping

> A ping tool that includes TCP ping, latency and bandwidth measurement.
> More information: <https://docs.microsoft.com/sysinternals/downloads/psping>.

- Ping a host using ICMP:

`psping {{hostname}}`

- Ping a host over a TCP port:

`psping {{hostname}}:{{port}}`

- Specify the number of pings and perform it quietly:

`psping {{hostname}} -n {{pings}} -q`

- Ping the target over TCP 50 times and produce a histogram of the results:

`psping {{hostname}}:{{port}} -q -n {{50}} -h`

- Display usage information:

`psping /?`

