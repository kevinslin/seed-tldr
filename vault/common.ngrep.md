---
id: common.ngrep
title: Ngrep
desc: ''
updated: 1623965306200
created: 1623965306200
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ngrep

> Filter network traffic packets using regular expressions.
> More information: <https://github.com/jpr5/ngrep>.

- Capture traffic of all interfaces:

`ngrep -d any`

- Capture traffic of a specific interface:

`ngrep -d {{eth0}}`

- Capture traffic crossing port 22 of interface eth0:

`ngrep -d {{eth0}} port {{22}}`

- Capture traffic from or to a host:

`ngrep host {{www.example.com}}`

- Filter keyword 'User-Agent:' of interface eth0:

`ngrep -d {{eth0}} '{{User-Agent:}}'`

