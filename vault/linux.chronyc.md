---
id: linux.chronyc
title: Chronyc
desc: ''
updated: 1642441815090
created: 1642441815090
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chronyc

> Query the Chrony NTP daemon.
> More information: <https://chrony.tuxfamily.org/doc/4.0/chronyc.html>.

- Start chronyc in interactive mode:

`chronyc`

- Display tracking stats for the Chrony daemon:

`chronyc tracking`

- Print the time sources that Chrony is currently using:

`chronyc sources`

- Display stats for sources currently used by chrony daemon as a time source:

`chronyc sourcestats`

- Step the system clock immediately, bypassing any slewing:

`chronyc makestep`

- Display verbose information about each NTP source:

`chronyc ntpdata`

