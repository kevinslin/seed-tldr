---
id: common.git-count-objects
title: Git Count Objects
desc: ''
updated: 1623965306187
created: 1623965306187
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git count-objects

> Count the number of unpacked objects and their disk consumption.
> More information: <https://git-scm.com/docs/git-count-objects>.

- Count all objects and display the total disk usage:

`git count-objects`

- Display a count of all objects and their total disk usage, displaying sizes in human readable units:

`git count-objects --human-readable`

- Display more verbose information:

`git count-objects --verbose`

- Display more verbose information, displaying sizes in human readable units:

`git count-objects --human-readable --verbose`

