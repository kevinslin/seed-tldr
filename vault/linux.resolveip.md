---
id: linux.resolveip
title: Resolveip
desc: ''
updated: 1642441815110
created: 1642441815110
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# resolveip

> Resolve hostnames to their IP addresses and vice versa.
> More information: <https://mariadb.com/kb/en/resolveip/>.

- Resolve a hostname to an IP address:

`resolveip {{example.org}}`

- Resolve an IP address to a hostname:

`resolveip {{1.1.1.1}}`

- Silent mode. Produces less output:

`resolveip --silent {{example.org}}`

