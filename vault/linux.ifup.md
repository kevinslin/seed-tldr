---
id: linux.ifup
title: Ifup
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
# ifup

> Tool used to enable network interfaces.
> More information: <https://manpages.debian.org/latest/ifupdown/ifup.8.html>.

- Enable interface eth0:

`ifup {{eth0}}`

- Enable all the interfaces defined with "auto" in `/etc/network/interfaces`:

`ifup -a`

