---
id: linux.utmpdump
title: Utmpdump
desc: ''
updated: 1623965306231
created: 1623965306231
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# utmpdump

> Dump and load btmp, utmp and wtmp accounting files.

- Dump the `/var/log/wtmp` file to the standard output as plain text:

`utmpdump {{/var/log/wtmp}}`

- Load a previously dumped file into `/var/log/wtmp`:

`utmpdump -r {{dumpfile}} > {{/var/log/wtmp}}`

