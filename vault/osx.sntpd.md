---
id: osx.sntpd
title: Sntpd
desc: ''
updated: 1644840636312
created: 1644840636312
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sntpd

> An SNTP server.
> It should not be invoked manually.
> More information: <https://linux.die.net/man/8/snmpd>.

- Start the daemon:

`sntpd`

- Overwrite existing state with the local clock (stratum 1), for running a master/primary server, without synchronizing with another (higher stratum) server:

`sntpd -L`

- Use a custom file for the SNTP state:

`sntpd -z {{path/to/state.bin}}`

