---
id: linux.getfacl
title: Getfacl
desc: ''
updated: 1615663978746
created: 1615663978746
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# getfacl

> Get file access control lists.

- Display the file access control list:

`getfacl {{path/to/file_or_directory}}`

- Display the file access control list with numeric user and group IDs:

`getfacl -n {{path/to/file_or_directory}}`

- Display the file access control list with tabular output format:

`getfacl -t {{path/to/file_or_directory}}`

