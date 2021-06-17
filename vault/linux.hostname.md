---
id: linux.hostname
title: Hostname
desc: ''
updated: 1623965016162
created: 1623965016162
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hostname

> Show or set the system's host name.

- Show current host name:

`hostname`

- Show the network address of the host name:

`hostname -i`

- Show all network addresses of the host:

`hostname -I`

- Show the FQDN (Fully Qualified Domain Name):

`hostname --fqdn`

- Set current host name:

`hostname {{new_hostname}}`

