---
id: common.stat
title: Stat
desc: ''
updated: 1642441815071
created: 1642441815071
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stat

> Display file and filesystem information.
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/stat-invocation.html>.

- Show file properties such as size, permissions, creation and access dates among others:

`stat {{file}}`

- Same as above but in a more concise way:

`stat -t {{file}}`

- Show filesystem information:

`stat -f {{file}}`

- Show only octal file permissions:

`stat -c "%a %n" {{file}}`

- Show owner and group of the file:

`stat -c "%U %G" {{file}}`

- Show the size of the file in bytes:

`stat -c "%s %n" {{file}}`

