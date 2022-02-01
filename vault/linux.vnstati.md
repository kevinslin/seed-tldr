---
id: linux.vnstati
title: Vnstati
desc: ''
updated: 1642441815117
created: 1642441815117
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vnstati

> PNG image output support for vnStat.
> More information: <https://manned.org/vnstati>.

- Output a summary of the last 2: months, days, and all-time:

`vnstati --summary --iface {{network_interface}} --output {{path/to/output.png}}`

- Output the 10 most traffic-intensive days of all time:

`vnstati --top10 --iface {{network_interface}} --output {{path/to/output.png}}`

- Output monthly traffic statistics from the last 12 months:

`vnstati --months --iface {{network_interface}} --output {{path/to/output.png}}`

- Output hourly traffic statistics from the last 24 hours:

`vnstati --hours --iface {{network_interface}} --output {{path/to/output.png}}`

