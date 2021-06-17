---
id: common.nbtscan
title: Nbtscan
desc: ''
updated: 1623965306198
created: 1623965306198
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nbtscan

> Scan networks for NetBIOS name information.
> More information: <https://github.com/resurrecting-open-source-projects/nbtscan>.

- Scan a network for NetBIOS names:

`nbtscan {{192.168.0.1/24}}`

- Scan a single IP address:

`nbtscan {{192.168.0.1}}`

- Display verbose output:

`nbtscan -v {{192.168.0.1/24}}`

- Display output in `/etc/hosts` format:

`nbtscan -e {{192.168.0.1/24}}`

- Read IP addresses / networks to scan from a file:

`nbtscan -f {{path/to/file.txt}}`

