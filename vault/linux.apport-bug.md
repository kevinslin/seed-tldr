---
id: linux.apport-bug
title: Apport Bug
desc: ''
updated: 1623965016158
created: 1623965016158
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apport-bug

> File a bug report on Ubuntu.
> More information: <https://wiki.ubuntu.com/Apport>.

- Report a bug about the whole system:

`apport-bug`

- Report a bug about a specific package:

`apport-bug {{package}}`

- Report a bug about a specific executable:

`apport-bug {{path/to/executable}}`

- Report a bug about a specific process:

`apport-bug {{PID}}`

