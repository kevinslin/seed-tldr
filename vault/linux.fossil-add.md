---
id: linux.fossil-add
title: Fossil Add
desc: ''
updated: 1642441815095
created: 1642441815095
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fossil add

> Put files or directories under Fossil version control.
> More information: <https://fossil-scm.org/home/help/add>.

- Put a file or directory under version control, so it will be in the current checkout:

`fossil add {{path/to/file_or_directory}}`

- Remove all added files from the current checkout:

`fossil add --reset`

