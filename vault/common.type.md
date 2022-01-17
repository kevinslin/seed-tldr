---
id: common.type
title: Type
desc: ''
updated: 1642441815078
created: 1642441815078
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# type

> Display the type of command the shell will execute.
> More information: <https://manned.org/type>.

- Display the type of a command:

`type {{command}}`

- Display all locations containing the specified executable:

`type -a {{command}}`

- Display the name of the disk file that would be executed:

`type -p {{command}}`

