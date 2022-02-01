---
id: linux.unset
title: Unset
desc: ''
updated: 1642441815115
created: 1642441815115
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unset

> Remove shell variables or functions.
> More information: <https://manned.org/unset>.

- Remove the variable `foo`, or if the variable doesn't exist, remove the function `foo`:

`unset {{foo}}`

- Remove the variables foo and bar:

`unset -v {{foo}} {{bar}}`

- Remove the function my_func:

`unset -f {{my_func}}`

