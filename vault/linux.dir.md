---
id: linux.dir
title: Dir
desc: ''
updated: 1642441815092
created: 1642441815092
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dir

> List directory contents using one line per file, special characters are represented by backslash escape sequences.
> Works as `ls -C --escape`.
> More information: <https://manned.org/dir>.

- List all files, including hidden files:

`dir -all`

- List files including their author (`-l` is required):

`dir -l --author`

- List files excluding those that match a specified blob pattern:

`dir --hide={{pattern}}`

- List subdirectories recursively:

`dir --recursive`

- Display help:

`dir --help`

