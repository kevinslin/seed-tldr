---
id: common.printenv
title: Printenv
desc: ''
updated: 1615663978730
created: 1615663978730
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# printenv

> Print values of all or specific environment variables.

- Display key-value pairs of all environment variables:

`printenv`

- Display the value of a specific variable:

`printenv {{HOME}}`

- Display the value of a variable and end with NUL instead of newline:

`printenv --null {{HOME}}`

