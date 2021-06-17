---
id: linux.unshadow
title: Unshadow
desc: ''
updated: 1623965016170
created: 1623965016170
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unshadow

> Utility provided by the John the Ripper project to obtain the traditional Unix password file if the system uses shadow passwords.
> More information: <https://www.openwall.com/john/>.

- Combine the `/etc/shadow` and `/etc/passwd` of the current system:

`sudo unshadow /etc/passwd /etc/shadow`

- Combine two arbitrary shadow and password files:

`sudo unshadow {{path/to/passwd}} {{path/to/shadow}}`

