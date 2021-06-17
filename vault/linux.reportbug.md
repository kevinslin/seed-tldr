---
id: linux.reportbug
title: Reportbug
desc: ''
updated: 1623965016167
created: 1623965016167
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# reportbug

> Bug report tool of Debian distribution.
> More information: <https://manpages.debian.org/buster/reportbug/reportbug.1.en.html>.

- Generate a bug report about a specific package, then send it by e-mail:

`reportbug {{package}}`

- Report a bug that is not about a specific package (general problem, infrastructure, etc.):

`reportbug other`

- Write the bug report to a file instead of sending it by e-mail:

`reportbug -o {{filename}} {{package}}`

