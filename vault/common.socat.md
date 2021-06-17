---
id: common.socat
title: Socat
desc: ''
updated: 1623965306210
created: 1623965306210
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# socat

> Multipurpose relay (SOcket CAT).

- Listen to a port, wait for an incoming connection and transfer data to STDIO:

`socat - TCP-LISTEN:8080,fork`

- Create a connection to a host and port, transfer data in STDIO to connected host:

`socat - TCP4:www.example.com:80`

- Forward incoming data of a local port to another host and port:

`socat TCP-LISTEN:80,fork TCP4:www.example.com:80`

