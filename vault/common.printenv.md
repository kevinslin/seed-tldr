---
id: common.printenv
title: Printenv
desc: ''
updated: 1642441815061
created: 1642441815061
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# printenv

> Print values of all or specific environment variables.
> More information: <https://www.gnu.org/software/coreutils/printenv>.

- Display key-value pairs of all environment variables:

`printenv`

- Display the value of a specific variable:

`printenv {{HOME}}`

- Display the value of a variable and end with NUL instead of newline:

`printenv --null {{HOME}}`

