---
id: linux.ntpq
title: Ntpq
desc: ''
updated: 1623965306226
created: 1623965306226
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ntpq

> Query the Network Time Protocol (NTP) daemon.
> More information: <https://www.eecis.udel.edu/~mills/ntp/html/ntpq.html>.

- Start `ntpq` in interactive mode:

`ntpq --interactive`

- Print a list of NTP peers:

`ntpq --peers`

- Print a list of NTP peers without resolving hostnames from IP addresses:

`ntpq --numeric --peers`

- Use `ntpq` in debugging mode:

`ntpq --debug-level`

- Print NTP system variables values:

`ntpq --command={{rv}}`

