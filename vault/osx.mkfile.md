---
id: osx.mkfile
title: Mkfile
desc: ''
updated: 1642441815121
created: 1642441815121
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkfile

> Create one or more empty files of any size.
> More information: <https://ss64.com/osx/mkfile.html>.

- Create an empty file of 15 kilobytes:

`mkfile -n {{15k}} {{filename}}`

- Create a file of a given size and unit (bytes, KB, MB, GB):

`mkfile -n {{size}}{{b|k|m|g}} {{filename}}`

- Create two files of 4 megabytes each:

`mkfile -n {{4m}} {{first_filename}} {{second_filename}}`

